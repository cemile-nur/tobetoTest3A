# tobetoTest3A

# Decorators

1. **@pytest.fixture**:
   Bu dekoratör, test fonksiyonlarına bağımlılık (dependency) sağlamak için kullanılır. Fixture'lar, testlerden önce belirli bir durumda veri hazırlamak veya ortamı ayarlamak için idealdir.

2. **@pytest.mark.parametrize**:
   Test fonksiyonlarını farklı veri setleri ile çalıştırmak için kullanılır. Bu, aynı testin farklı girdilerle çalıştırılmasını sağlar.

3. **@pytest.mark.skip**:
   Bu dekoratör, belirli bir koşula bağlı olarak testin atlanmasını sağlar. Örneğin, belirli bir durumu kontrol ederek testin çalıştırılmamasını sağlayabilirsiniz.

4. **@pytest.mark.skipif**:
   Bu dekoratör, belirli bir koşul doğru olduğunda testin atlanmasını sağlar. Koşulu bir ifade olarak belirtirsiniz.

5. **@pytest.mark.xfail**:
   Bu dekoratör, testin başarısız olmasının beklendiği durumlarda kullanılır. Bu, bilinen hataları yönetmek için faydalıdır.

6. **@pytest.mark.usefixtures**:
   Bu dekoratör, belirli fixture'ların test fonksiyonu tarafından kullanılmasını sağlar. Bu, fixture'ların otomatik olarak uygulanmasını sağlar.

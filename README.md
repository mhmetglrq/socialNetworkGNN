# GNN ile Twitter Higgs Veri Seti Üzerinde Topluluk Tespiti

Bu proje, **PyTorch Geometric (PyG)** kullanarak **Twitter Higgs** veri setinde topluluk tespiti yapmayı amaçlar. Veri seti, bir sosyal ağ grafiğini temsil eder ve GNN (Graph Neural Network) ile düğümlerin topluluk etiketlerini tahmin etmek için kullanılır.

---

## Proje İçeriği

### Adımlar:
1. **Veri Seti İşleme**: 
   - [Twitter Higgs veri seti](https://networkrepository.com/soc-twitter-higgs.php) işlenerek bir grafik yapısına dönüştürüldü.
   - PyTorch Geometric formatına uygun hale getirildi.
2. **GNN Modeli Oluşturma**:
   - Basit bir **Graph Convolutional Network (GCN)** modeli tanımlandı.
3. **Model Eğitimi**:
   - Model, topluluk etiketlerini tahmin etmek üzere eğitildi.
4. **Sonuçların Görselleştirilmesi**:
   - Alt küme seçilerek topluluklar görselleştirildi.

---

## Veri Seti Hakkında

**Twitter Higgs veri seti**, **Network Repository** üzerinde barındırılan bir sosyal ağ grafiğidir. Bu veri seti, **Higgs bozonunun keşfi** sırasında Twitter'da oluşan bağlantıları içerir ve kullanıcıların takip ilişkilerini gösterir.

- **Bağlantı**: [Twitter Higgs Veri Seti - Network Repository](https://networkrepository.com/soc-twitter-higgs.php)
- **Dosya Formatı**: `.edges` (Kenar listesi)
- **Veri Özeti**:
  - **Düğümler (Nodes)**: Twitter kullanıcılarını temsil eder.
  - **Kenarlar (Edges)**: Kullanıcılar arasındaki takip ilişkilerini temsil eder.

---

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gereklidir:

- **Python 3.7+**
- **PyTorch**
- **PyTorch Geometric**
- **NetworkX**
- **Matplotlib**
- **Pandas**

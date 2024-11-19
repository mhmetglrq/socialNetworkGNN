# GNN ile Twitter Higgs Veri Seti Üzerinde Topluluk Tespiti

Bu proje, **PyTorch Geometric (PyG)** kullanarak **Twitter Higgs** veri setinde topluluk tespiti yapmayı amaçlar. Veri seti, bir sosyal ağ grafiğini temsil eder ve GNN (Graph Neural Network) ile düğümlerin topluluk etiketlerini tahmin etmek için kullanılır.

---

## Proje İçeriği

### Adımlar:
1. **Veri Seti İşleme**: 
   - Twitter Higgs veri seti işlenerek bir grafik yapısına dönüştürüldü.
   - PyTorch Geometric formatına uygun hale getirildi.
2. **GNN Modeli Oluşturma**:
   - Basit bir **Graph Convolutional Network (GCN)** modeli tanımlandı.
3. **Model Eğitimi**:
   - Model, topluluk etiketlerini tahmin etmek üzere eğitildi.
4. **Sonuçların Görselleştirilmesi**:
   - Alt küme seçilerek topluluklar görselleştirildi.

---

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gereklidir:

- **Python 3.7+**
- **PyTorch**
- **PyTorch Geometric**
- **NetworkX**
- **Matplotlib**
- **Pandas**

### Colab'de Gerekli Kurulum

Eğer Colab'de çalışıyorsanız, aşağıdaki kodları çalıştırarak gerekli kurulumları yapabilirsiniz:

```bash
# PyTorch ve PyTorch Geometric kur
!pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
!pip install torch-geometric

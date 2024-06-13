# First Part of a Project: 

#### Data Preparation

**Data Preparation Experiment 1**: Exp_1_data_preparation.ipynb

**Data Preparation Experiment 2**: Exp_2_data_preparation.ipynb, Exp_2_data_preparation-with-saving.ipynb

#### Experiment 1

**Experiment 1**: Two_Object_CNN_and_RNA.ipynb

**Experiment 1 Model**: normal_cnn_epoch_100.pth

#### Experiment 2

**Experiment 2**: Exp_2_cnn.ipynb

**Experiment 2 Model**: modelbest.pth

# Second Part of a Project: 
# Projekt: Segmentacja Obrazów i Modelowanie RNA

## 1. U-Net

**Plik:** U-NET.ipynb

Pierwsze podejście do segmentacji obrazów za pomocą sieci U-Net. W tym notebooku wykorzystano podstawową architekturę U-Net, a na końcu zaimplementowano algorytm w stylu k-means w celu poprawy wyników segmentacji. Podejście to stanowiło bazę do dalszych optymalizacji i eksperymentów.

## 2. Final U-Net

**Plik:** Final-UNET.ipynb

Ten notebook zawiera kilka podejść do segmentacji obrazów za pomocą sieci U-Net, z których każde było iteracyjnie udoskonalane. Finalne podejście zawarte w tym notebooku okazało się być najbardziej wydajne i przyniosło najlepsze wyniki w kontekście dokładności segmentacji.

## 3. Modelowanie RNA

**Plik:** Two_Object_CNN_and_RNA.ipynb

Notebook ten prezentuje zastosowanie konwolucyjnych sieci neuronowych (CNN) do modelowania RNA. W projekcie tym zbudowano model CNN do klasyfikacji sekwencji RNA, uwzględniając specyficzne cechy strukturalne RNA, które mają kluczowe znaczenie dla poprawy wyników klasyfikacji.

## 4. Porównanie Modeli RNA

**Modele:** rna_cnn_epoch_50.pth, normal_cnn_epoch_50.pth

Dla porównania wydajności modeli RNA wykorzystano dwa różne modele zapisane w formacie `.pth`:
- **rna_cnn_epoch_50.pth**: Model trenowany przez 50 epok, zoptymalizowany do klasyfikacji sekwencji RNA.
- **normal_cnn_epoch_50.pth**: Model trenowany przez 50 epok, służący jako punkt odniesienia do oceny wydajności zoptymalizowanego modelu RNA.

Podsumowanie wyników obu modeli oraz ich porównanie znajduje się w odpowiednich sekcjach notebooka `Two_Object_CNN_and_RNA.ipynb`.

---

Projekt ten pokazuje różnorodność podejść do problemów segmentacji obrazów oraz modelowania RNA, demonstrując siłę i wszechstronność konwolucyjnych sieci neuronowych.


**RNA**: Two_Object_CNN_and_RNA.ipynb

**RNA Model**: rna_cnn_epoch_50.pth i dla porównania normal_cnn_epoch_50.pth


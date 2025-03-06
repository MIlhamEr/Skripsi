# Planning eksperimen
1. Mulai dengan 50 neuron dan 2 layer.
2. Ganti 100 neuron untuk kompleksitas representasi data.

   Lebih banyak neuron → Model dapat menangkap pola yang lebih kompleks dalam data.

   Lebih sedikit neuron → Model lebih sederhana dan bisa menghindari overfitting.
4. Bandingkan dropout 0.2 vs. 0.4 untuk melihat efek overfitting.
5. Pakai EarlyStopping dan tanpa EarlyStopping.
# Eksperimen
## LSTM
1. versi 5 -> 50 neu, do 0.2, tanpa ES
2. versi 6 -> 100 neu, do 0.2, tanpa ES
# ===========📊 EDA 📊============
https://colab.research.google.com/drive/1VcfTKWuIh0CyMwh4eS11GKPFQz9bPB-v?usp=sharing
# ===========✨ LSTM ✨===========
https://colab.research.google.com/drive/1tbSDgGS6dMjt3G_F2PbEuaJO_MH_yUjQ?usp=sharing
## LSTM 1
Kayaknya preprocessingnya masih salah
1. Dataset ADRO -> Udah bagus
2. Dataset DSSA -> Overfitting
## LSTM 4
udh fix???
# ===========🔆 GRU 🔆===========
https://colab.research.google.com/drive/15V_ERnpr1VVuQXn2TuTb80fx8AaWpRCo?usp=sharing
## GRU 1
Preprocessingnya better than LSTM
1. Dataset ADRO -> Udah bagus
2. Dataset DSSA -> Overfitting
## GRU 2
Untuk DSSA pakai EarlyStopping untuk menghentikan training ketika val_loss naik terus
## GRU 4
udh fix???

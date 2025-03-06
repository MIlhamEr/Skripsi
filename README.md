# Planning eksperimen
1. Mulai dengan 50 neuron, 1-2 layer, dan learning rate 0.001.
2. Coba window size yang berbeda (misalnya 10 vs. 20 hari).
3. Bandingkan dropout 0.2 vs. 0.3 untuk melihat efek overfitting.
4. Uji batch size kecil (32) vs. besar (128) untuk kecepatan training.
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

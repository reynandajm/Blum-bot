### Cara Menclone dan menjalankan bot

1. **Clone the repository:**
    ```bash
    git clone https://github.com/reynandajm/Blum-bot.git
    ```

2. **Run script:**
	Double-click  `run.bat` (windows) atau `bash run.sh` (linux or macos) 

### Configuration

Edit file `data/config.py` menggunakan `API_ID` and `API_HASH` telegram anda

```python
API_ID = 'your_api_id'
API_HASH = 'your_api_hash'
```

### **Mendapatkan API dan HASH Telegram

1. Login ke https://my.telegram.org/auth, menggunakan no. HP telegram anda
2. Kemudian pilih API Development Tools

   ![image](https://github.com/user-attachments/assets/b09bbbcb-7488-4b2d-bacb-cc4740ee540c)
   
3. Selanjutnya isi form untuk membuat Aplikasi *anda bebas untuk mengisi apapun
   
   ![image](https://github.com/user-attachments/assets/9cbf7249-f5fd-40b3-b538-1d89b2acf167)

4. Copy API_ID dan API_HASH ke dalam file `data/config.py` kemudian save dan lanjut ke step berikutnya
   
   ![image](https://github.com/user-attachments/assets/23db9637-3061-4a18-a581-699fcfab871e)

### Usage


1. **Run the script:**
    ```run.bat``` or ```run.sh```

2. **Select an action:**
    - `1` create session
    - `2` run clicker

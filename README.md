# Hướng dẫn làm lab
## Tải lab
```bash
imodule https://github.com/chinh310503/stego_code_stsm/raw/main/imodule.tar
```

## Task 1: giấu tin vào trong file âm thanh

- Giấu tin vào trong file âm thanh
```bash
python3 hide.py
```

- Chuyển file âm thanh sang cho bob giải mã
```bash
scp output.wav bob@ip_bob:/home/bob
```

## Task 2: Giải mã thông tin có trong file âm thanh
```bash
python3 extract.py
```

## Task3: Đọc thông tin đã được giấu trong file âm thanh
```bash
cat data.txt
```

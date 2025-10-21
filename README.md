# ITM-https://github.com/sawl123/ITM-/blob/main/README.md
homework 4

Exercise 1
with open('yesterday.txt', 'r') as f:
    yesterday_lyric = f.read()
    
yesterday_lyric = yesterday_lyric.lower()

count = yesterday_lyric.count('yesterday')

print("yesterday 개수:", count)

출력결과(image) <img width="1180" height="86" alt="image" src="https://github.com/user-attachments/assets/fbd763b1-f7cc-419f-96d1-84f8360af8fe" />


Exercise 2 

with open('yesterday.txt', 'r', encoding='utf-8') as f:
    lyric = f.read()

count_Yesterday = lyric.count('Yesterday')   # 대문자 Y
count_yesterday = lyric.count('yesterday')   # 소문자 y

print("Yesterday 개수:", count_Yesterday)
print("yesterday 개수:", count_yesterday)


출력결과(image) <img width="467" height="168" alt="image" src="https://github.com/user-attachments/assets/b320ff56-ef6e-4775-807c-e190be9499b4" />


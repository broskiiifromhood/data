echo "Sample data content" > data.txt

git add data.txt
git commit -m "Add data file"
git push origin main

# read_data.py 파일

# data.txt 파일 읽고 출력하는 코드
with open('data.txt', 'r') as file:
    data = file.read()

print(data)

python read_data.py


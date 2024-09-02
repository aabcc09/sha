git clone https://github.com/xiaoli/simple-calculator.git
cd simple-calculator
echo "def add(a, b):" > calculator.py
echo "    return a + b" >> calculator.py
echo "" >> calculator.py
echo "def subtract(a, b):" >> calculator.py
echo "    return a - b" >> calculator.py

git add calculator.py
git commit -m "Add basic addition and subtraction functions"
git push origin main

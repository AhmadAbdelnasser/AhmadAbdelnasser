- 👋 Hi, I’m @AhmadAbdelnasser
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
AhmadAbdelnasser/AhmadAbdelnasser is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import random

def generate_random_numbers(num_numbers):
    random_numbers = [
1
3
5
7
9
    for _ in range(num_numbers):
        # Replace this with the actual data from your TRNG
        random_data = random.randint(0, 255)  # Simulating TRNG data (0-255 for example)
        random_numbers.append(random_data)
    return random_numbers

next_5_random_numbers = generate_random_numbers(5)
print(next_5_random_numbers)

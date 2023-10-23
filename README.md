    - 👋 Hi, I’m @GCC1111
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
GCC1111/GCC1111 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def fibonacci(n)
  return n if ( 0..1 ).include? n
  (fibonacci(n - 1) + fibonacci(n - 2)) #recursive calls
end
def fibonacci(n)
  return n if ( 0..1 ).include? n
  (fibonacci(n - 1) + fibonacci(n - 2)) #recursive calls
end
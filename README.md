- 👋 Hi, I’m @mhunte37
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
mhunte37/mhunte37 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def binary_search(arr, value, offset=0)
  mid =  (arr.length) / 2
  
  if value < arr[mid] binary_search(arr[0...mid], value, offset) elsif value > arr[mid]
     binary_search(arr[(mid + 1)..-1], value, offset + mid + 1)
  
  else
     return offset + mid
  end

end

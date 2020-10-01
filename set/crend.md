# back

**Description** : It returns a const_reverse_iterator pointing to the element that would theoretically precede the first element in the container.

**Example**:
```cpp
    std::set<int> myset = {50,40,30,20,10};

   std::cout << "myset backwards:";
   for (auto rit = myset.crbegin(); rit != myset.crend(); ++rit)
      std::cout << ' ' << *rit;

   std::cout << '\n';
```
**[Run Code](https://rextester.com/RBRA89398)**

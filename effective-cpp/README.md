# Effective CPP (3rd Edition)

### if you use \#define, remind const, enum, inline.

```cpp
#define CALL_MAX(a, b) f((a) > (b) ? (a) : (b))
```

instead of obove code. using inline code like this :

```cpp
template<typename T>
inline void callMax(const T& a, const T& b){
	f(a > b ? a : b);
}
```

### if you feel something, using const.

### initialize the object, before you using.

example code :

```cpp
int x = 0;	// direct initialized.
const char * text = "A C-style string";	// direct initialization of pointers.
double d;
std::cin >> d;	// by reading from the input stream. initialized.
```

using cpp initializer. 

### keep the exception from leaving the destructor.

```cpp
class Widget{ 
public:
	...
	~Widget(){ ... }       // exception occur! in this func.
};

void doSomething(){
	std::vector<Widget> v;
	...
}                        // object v. it automatically disappears.
```

###  

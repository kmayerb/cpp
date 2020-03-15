# cpp
an idiosyncratic cpp cheatsheet

Essential syntax which is completely foreign to python.

## x > y ? x : y

ternary conditinal opperator.  

```cpp
main(){
    int x = 5;
    int y = 1;
    printf("True, so return x or %d\n", x > y ? x : y);
    printf("False, so return y or %d\n", x < y ? x : y);
}
```
```
True, so return x or 5
False, so return y or 1
```

## switch(x)

```cpp
int main() {
    int x = 2;

    switch(x) {
        case 1:
            puts("x == 1");
            break;
        case 2:
            puts("x == 2");
            break;
        default:
            puts("x != 1 or 2");
            break;
    }
}

```

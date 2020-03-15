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
    const int a = 1;
    const int b = 2;
    
    int x = 2;

    switch(x) {
        case a:
            puts("x == 1");
            break;
        case b:
            puts("x == 2");
            break;
        default:
            puts("x != 1 or 2");
            break;
    }
}

```

## do while


```cpp
int main()
{
    int array[] = { 1, 2, 3 };
    int i = 0;
    
    do {
        printf("%d\n", array[i]);
        ++i;
    } while(i < 3);
    
    return 0;
}
```


## for

```cpp
int main()
{
    // basic for loop
    for( int i = 0; i < 5; ++i ) {
        printf("i is %d\n", i);
    }
    return 0;
}
```

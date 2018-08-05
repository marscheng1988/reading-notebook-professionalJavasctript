# javascript notebook

## 原型和原型链
    ^只要创建一个函数，就会自动为改函数创建一个prototype属性，这个属性指向函数的原型对象。
    所有原型对象都会自动获得一个constructor（构造函数）属性，这个属性包含一个指向prototype属性所在函数的指针
    （每个函数都有prototype属性，都可以成为构造函数，都可以被new。new出来的新实例，继承prototype的所有属性
    ![Alt text](./WX20180805-174418@2x.png)

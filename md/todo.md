
所以在 js 中能够安全使用的有符号 安全 大整数（注意这里是指能够安全使用，进行算数运算的范围），并不像其他语言在 64 位环境中那样是:

2^63 - 1;//9223372036854775807
而是

Math.pow(2, 53) - 1     // 9007199254740991

JS 的最大和最小安全值可以这样获得:

console.log(Number.MAX_SAFE_INTEGER); //9007199254740991
console.log(Number.MIN_SAFE_INTEGER); //-9007199254740991


发行总量为2的52次方

不挖矿，而是参考IOTA发行

https://steemit.com/cn/@peterchen145/iota

每个人可以follow其他人



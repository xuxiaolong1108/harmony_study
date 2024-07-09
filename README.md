# ArkTs基本语法
### 接口
interface Person {
  name:string;
  age:number;
  dance:() => void;
}

let pserson:Person ={
  name :'',
  age:3,
  dance:()=>{

  }
}
### 箭头函数
let star = (aaa:string)=>{
  return aaa;
}
### 联合变量
let aaa:string|number;
aaa ='www';
aaa =123;
let gender: 'man' | 'women' = 'man'

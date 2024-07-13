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

# ArkUi语法
绝对定位 (原本的位置不占用，这个元素独立了)
.position({
        x:50,
        y:50
      })
 
 层级 .zIndex(1)

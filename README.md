# js-valuesFrom

function valuesFrom(obj){
 const o=obj,m=Object.keys(o),l=m.length;
 for(let i=0;i<l;++i){m[i]=o[m[i]];};
 return m;
};

console.dir(valuesFrom({a:1,b:2,c:3}));//[1, 2, 3]

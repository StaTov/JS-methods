# String
<strong>String.prototype.at(value)</strong>
<br/>
<i>value:</i> 1 | -1  (Number)
<br/>
<i>return:</i> 'a' | undefined
<br/>
'Hello world'.at(-1)  // 'd'
<hr/>
<strong>String.prototype.charAt(index)</strong>
<br/>
<i>index:</i> 0 | 99 (Number)
<br/>
<i>return:</i> 'a' | ' '
<br/>
'Hello world'.charAt(6)  // 'w'
<hr/>
<strong>String.prototupe.concat(string2, string3[, ..., stringN])</strong>
<br/>
<i>string2:</i>  (String)
<br/>
<i>return:</i> 'string'
<br/>
console.log('Hello'.concat(' ', 'world'))  // 'Hello world'
<br/>
Please use +  += instead concat
<hr/>
<strong>String.prototype.endsWith(searchString[, length])</strong>
<br/>
<i>searchString:</i> 'string'
<br/>
<i> length</i> урезать длину строки
<br/>
<i>return:</i> true | false
<br/>
'Hello world'.endsWith('world')  // true
<hr/>
<strong>String.prototype.includes(searchString[, position])</strong>
<br/>
<i>searchString:</i> (String)
<br/>
<i>position</i> 0 | 999 (Number) Позиция начала поиска
<br/>
<i>return:</i> true | false
<br/>
'Hello world'.includes('ello')  // true
<br/>
'Hello world'.includes('ello', 3)  // false
<hr/>
<strong>String.prototype.indexOf(searchValue, [fromIndex)</strong>
<br/>
<i>searchValue</i> (String)
<br/>
<i>fromIndex</i> 0 | 999  (Number)
<br/>
<i>return:</i> index('number') | -1
<br/>
'Hello world'.indexOf('world')  // 6
<br/> 
'Hello world'.indexOf('red')   // -1
<hr/>
<strong>String.prototype.lastIndexOf(searchValue, [fromIndex)</strong>
<br/>
<i>searchValue</i> (String)
<br/>
<i>fromIndex</i> 0 | 999  (Number)
<br/>
<i>return:</i> index последнего вхождения ('number') | -1
<br/>
'Hello world'.indexOf('world')  // 6
<br/> 
'canal'.lastIndexOf('a'); //  3   
<hr/>
# Number

# Array

# Object



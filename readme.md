<h1>Qlik Sense Script Cheatsheet</h1>
<p>
  <li>Choose non-zero dimensions --> IF((MyField)<>0, MyField)</li>
  <li>Empty cells not recognised as null --> len(trim(MyField))>0</li>  
  <li>Checking blank, empty etc --> IF((MyField='BLANK' or MyField='NULL' or MyField='' or isNULL(X_COURSE_TYPE) or len(MyField)>0)</li>
  <li></li>
</p>  

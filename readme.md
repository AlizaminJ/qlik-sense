<h1>Qlik Sense Script</h1>
<p>
  <li>Empty cells not recognised as null --> len(trim(MyField))>0</li>  
  <li>Choose non-zero dimensions --> IF((MyField)<>0, MyField)</li>
</p>  

=if((X_COURSE_TYPE='BLANK' or X_COURSE_TYPE='NULL' or X_COURSE_TYPE='' or isNULL(X_COURSE_TYPE) or len(trim(X_COURSE_TYPE))>0), 'BLANK', X_COURSE_TYPE)

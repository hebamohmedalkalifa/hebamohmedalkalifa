<?php 
session_start ( );
 ?>
 <!DOCTYPE html >
< html >
< الرأس >
< مجموعة ميتا = "utf-8" >
< اسم التعريف = محتوى "viewport" = "عرض = عرض الجهاز ، المقياس الأولي = 1" >
< العنوان > في < / العنوان >

< / head >
< الجسم >
<?php 
if ( $ _POST [ "name" ] = "admin" & = _POST $ "pass" [ ] "123" =

$ _SESSION [ 'me' ] = 'YES';
صدى "لقد قمت بتسجيل الدخول بنجاح";
صدى "< br >";
echo '< a href = "http://localhost/phptota/hello.php">'."Go لتحرير الصفحة";
}
آخر {
session_start ( );
$ _SESSION [ 'me' ] = 'NO';
صدى "خطأ";
 
}

?>
< / الجسم >
< / html >

# test_openshift

http://register-php157.rhcloud.com/
http://test-php157.rhcloud.com/


IF php/ dir exists THEN DocumentRoot=php/  
ELSE IF public/ dir exists THEN DocumentRoot=public/  
ELSE IF public_html/ dir exists THEN DocumentRoot=public_html/  
ELSE IF web/ dir exists THEN DocumentRoot=web/  
ELSE IF www/ dir exists THEN DocumentRoot=www/  
ELSE DocumentRoot=/ 

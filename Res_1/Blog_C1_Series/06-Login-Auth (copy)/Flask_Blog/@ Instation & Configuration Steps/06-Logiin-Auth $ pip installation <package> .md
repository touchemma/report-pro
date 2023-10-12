## REQUIRED PACKAGES AT LOGIN AUTH & TESTING
* 06-Logiin-Auth $ pip installation <package> 
- $ pip install flask-bcrypt
- $ python3 enter
- >>> from flask_bcrypt import Bcrypt
- >>> bcrypt =  Bcrypt() 
- >>> bcrypt.generate_password_hash(testing)
-     b$'aaaabbb'
- >>> bcrypt.generate_password_hash(testing).decode('utf-8)
-      $'2baaaabbb'
- >>> bcrypt.generate_password_hash(testing).decode('utf-8)      
- >>> bcrypt.generate_password_hash(testing).decode('utf-8)
-      $'2caaaabbb'
# Verification of right password
- >>> hashed_pwd = bcrypt.generate_password_hash(testing).decode('utf-8)     
- >>> bcrypt.check_password_hash(hashed_pwd, 'password')
-      False
- >>> bcrypt.check_password_hash(hashed_pwd, 'testing')
      * True

- >>> exit()

-     [CLICK TO VIEW THE CODE]()

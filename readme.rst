###################
SmsGatewayMe
###################

a Sms Gateway library for Codeigniter. 

*******************
Installation
*******************

Copy sms.php in libraries/Sms.php into your libraries folder

**************************
Use
**************************
- Controller
```
// initialize email and password
$email = "";
$password = "";
$lib = array('email'=>$email,'password'=>$password);
$this->load->library('Sms',$lib);

$this->Sms->someMethod();
```

Full documentation on https://smsgateway.me

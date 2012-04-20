JSMSAPI
=======

Send free unlimited SMS using Java

Example:

way2sms.com

    SMS sms = new Way2SMS();
    sms.login("9999999999", "passwd");
    System.out.println(sms.isAuthenticated());
    try {
        sms.send("8374566903", "hi!");
        sms.send("8374566903", "hello!!");
    } catch (NotAuthenticatedException ex) {
        ex.printStackTrace();
    }
    
160by2.com

    SMS sms = new SMS160by2();
    sms.login("9999999999", "passwd");
    System.out.println(sms.isAuthenticated());
    try {
        sms.send("8374566903", "hi!");
        sms.send("8374566903", "hello!!");
    } catch (NotAuthenticatedException ex) {
        ex.printStackTrace();
    }

fullonsms.com

    SMS sms = new FullonSMS();
    sms.login("9999999999", "passwd");
    System.out.println(sms.isAuthenticated());
    try {
        sms.send("8374566903", "hi!");
        sms.send("8374566903", "hello!!");
    } catch (NotAuthenticatedException ex) {
        ex.printStackTrace();
    }
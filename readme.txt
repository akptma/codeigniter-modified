CodeIgniter 3 http://codeigniter.com/
    - BaseUrl dynamic
    - index.php have been deleted
    - Add htaccess
    - Add TimeZone Asia/Jakarta
    - Add Carbon
    - Fixed "The Encrypt library requires the Mcrypt extension"
        - https://stackoverflow.com/questions/35798048/php-error-the-encrypt-library-requires-the-mcrypt-extension-in-codeigniter
    - Autoload 
        - $autoload['libraries']    = array('encrypt');
        - $autoload['helper']       = array('url', 'dump');
    - Config
        - $config['encryption_key']     = 'Your Key';
        - $config['composer_autoload']  = FCPATH . '/vendor/autoload.php'; //For Using Vendor

Vendor
    - Carbon : https://carbon.nesbot.com/docs/
        Example : https://try-carbon-lib.herokuapp.com/?hide-output-gutter&output-left-padding=10&theme=tomorrow_night&border=none&radius=4&v-padding=15&input=%24date%20%3D%20Carbon%3A%3Aparse(%272018-03-16%2015%3A45%27)-%3Elocale(%27uk%27)%3B%0A%0Aecho%20%24date-%3EtranslatedFormat(%27g%3Ai%20a%20l%20jS%20F%20Y%27)%3B%20%2F%2F%203%3A45%20%D0%B4%D0%BD%D1%8F%20%D0%BF%E2%80%99%D1%8F%D1%82%D0%BD%D0%B8%D1%86%D1%8F%2016-%D0%B3%D0%BE%20%D0%B1%D0%B5%D1%80%D0%B5%D0%B7%D0%BD%D1%8F%202018%0A&token=live-editor-23

helper 
    - Dump Helper : https://joostvanveen.com/a-3/dump-helper-alternative-var_dump

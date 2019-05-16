# SSL-certificate-verification-error-pydev-eclipse
the SSL certificate verification error that arises when we try to upgrade or install python or pip versions on command prompt
this issue arrived when i wanted to install pytest library for python

these are the errors u get
C:\Users\jak> pip install --upgrade pip 
Retrying (Retry(total=4, connect=None, read=None, redirect=None, status=None)) after connection broken by 'SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)': /simple/pip/
Retrying (Retry(total=3, connect=None, read=None, redirect=None, status=None)) after connection broken by 'SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)': /simple/pip/
Retrying (Retry(total=2, connect=None, read=None, redirect=None, status=None)) after connection broken by 'SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)': /simple/pip/
Retrying (Retry(total=1, connect=None, read=None, redirect=None, status=None)) after connection broken by 'SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)': /simple/pip/
Retrying (Retry(total=0, connect=None, read=None, redirect=None, status=None)) after connection broken by 'SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)': /simple/pip/
Could not fetch URL https://pypi.python.org/simple/pip/: There was a problem confirming the ssl certificate: HTTPSConnectionPool(host='pypi.python.org', port=443): Max retries exceeded with url: /simple/pip/ (Caused by SSLError(SSLError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:833)'),)) - skipping


C:\Users\jak> pip --version
pip 9.0.3 from c:\users\morten.sensio\appdata\local\programs\python\python36-32\lib\site-packages (python 3.6)
C:\Users\jak> python --version
Python 3.6.5
1.first upgrade the version python to 3.7.3
2.upgrade the pip version to 19.1.1
    while doing this use commamnd- 

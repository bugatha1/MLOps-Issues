# VMWare



SSH need to enable in server machine also.

  https://visualgdb.com/tutorials/linux/ubuntu/hyper-v/ 


Installing anaconda3 in ubuntu

  https://www.rosehosting.com/blog/how-to-install-anaconda-on-ubuntu-20-04/ 

  https://linuxhint.com/install_anaconda_ubuntu/


Create env in a specific path instead of conda

    Use the --prefix or -p option to specify where to write the environment files. For example:

    conda create --prefix /tmp/test-env python=2.7
    Will create the environment named /tmp/test-env which resides in /tmp/ instead of the default .conda.
    
    
``` 
If you can't find conda .. then add anaconda scripts path in environment varialbes.

C:\Users\umasa\anaconda3

C:\Users\umasa\anaconda3\Scripts
```

```
 Fetching package metadata ...
    CondaHTTPError: HTTP 000 CONNECTION FAILED for url <https://conda.anaconda.org/a
    naconda/win-64/repodata.json>
    Elapsed: -
    
    An HTTP error occurred when trying to retrieve this URL.
    HTTP errors are often intermittent, and a simple retry will get you on your way.
    
    https://stackoverflow.com/questions/50125472/issues-with-installing-python-libraries-on-windows-condahttperror-http-000-co
```

```
source base activate before conda env activate

source activate base
```


https://github.com/lpatruno/sagemaker-course

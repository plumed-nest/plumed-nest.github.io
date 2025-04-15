**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1719-82:69184] *** Process received signal ***
[fv-az1719-82:69184] Signal: Aborted (6)
[fv-az1719-82:69184] Signal code:  (-6)
[fv-az1719-82:69184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f53e6045330]
[fv-az1719-82:69184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f53e609eb2c]
[fv-az1719-82:69184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f53e604527e]
[fv-az1719-82:69184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53e60288ff]
[fv-az1719-82:69184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53e64a5ff5]
[fv-az1719-82:69184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53e64bb0da]
[fv-az1719-82:69184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53e64a5a55]
[fv-az1719-82:69184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53e64a5a6f]
[fv-az1719-82:69184] [ 8] plumed(+0x146dd)[0x559f3518a6dd]
[fv-az1719-82:69184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f53e602a1ca]
[fv-az1719-82:69184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f53e602a28b]
[fv-az1719-82:69184] [11] plumed(+0x15365)[0x559f3518b365]
[fv-az1719-82:69184] *** End of error message ***
</pre>
{% endraw %}

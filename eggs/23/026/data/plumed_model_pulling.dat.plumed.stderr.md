**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1665-105:06289] *** Process received signal ***
[fv-az1665-105:06289] Signal: Aborted (6)
[fv-az1665-105:06289] Signal code:  (-6)
[fv-az1665-105:06289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca12845330]
[fv-az1665-105:06289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca1289eb2c]
[fv-az1665-105:06289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca1284527e]
[fv-az1665-105:06289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca128288ff]
[fv-az1665-105:06289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca12ca5ff5]
[fv-az1665-105:06289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca12cbb0da]
[fv-az1665-105:06289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca12ca5a55]
[fv-az1665-105:06289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca12ca5a6f]
[fv-az1665-105:06289] [ 8] plumed(+0x146dd)[0x558d5ca026dd]
[fv-az1665-105:06289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca1282a1ca]
[fv-az1665-105:06289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca1282a28b]
[fv-az1665-105:06289] [11] plumed(+0x15365)[0x558d5ca03365]
[fv-az1665-105:06289] *** End of error message ***
</pre>
{% endraw %}

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
[fv-az1360-658:06627] *** Process received signal ***
[fv-az1360-658:06627] Signal: Aborted (6)
[fv-az1360-658:06627] Signal code:  (-6)
[fv-az1360-658:06627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ba4845330]
[fv-az1360-658:06627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ba489eb2c]
[fv-az1360-658:06627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ba484527e]
[fv-az1360-658:06627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ba48288ff]
[fv-az1360-658:06627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ba4ca5ff5]
[fv-az1360-658:06627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ba4cbb0da]
[fv-az1360-658:06627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ba4ca5a55]
[fv-az1360-658:06627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ba4ca5a6f]
[fv-az1360-658:06627] [ 8] plumed(+0x146dd)[0x55dd7fdb46dd]
[fv-az1360-658:06627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ba482a1ca]
[fv-az1360-658:06627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ba482a28b]
[fv-az1360-658:06627] [11] plumed(+0x15365)[0x55dd7fdb5365]
[fv-az1360-658:06627] *** End of error message ***
</pre>
{% endraw %}

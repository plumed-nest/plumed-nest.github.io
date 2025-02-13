**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1665-105:06305] *** Process received signal ***
[fv-az1665-105:06305] Signal: Aborted (6)
[fv-az1665-105:06305] Signal code:  (-6)
[fv-az1665-105:06305] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f634a845330]
[fv-az1665-105:06305] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f634a89eb2c]
[fv-az1665-105:06305] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f634a84527e]
[fv-az1665-105:06305] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f634a8288ff]
[fv-az1665-105:06305] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f634aca5ff5]
[fv-az1665-105:06305] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f634acbb0da]
[fv-az1665-105:06305] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f634aca5a55]
[fv-az1665-105:06305] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f634aca5a6f]
[fv-az1665-105:06305] [ 8] plumed_master(+0x146dd)[0x55b6b120e6dd]
[fv-az1665-105:06305] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f634a82a1ca]
[fv-az1665-105:06305] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f634a82a28b]
[fv-az1665-105:06305] [11] plumed_master(+0x15365)[0x55b6b120f365]
[fv-az1665-105:06305] *** End of error message ***
</pre>
{% endraw %}

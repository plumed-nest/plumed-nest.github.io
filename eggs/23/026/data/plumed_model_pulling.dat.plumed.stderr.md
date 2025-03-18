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
[fv-az1983-395:62161] *** Process received signal ***
[fv-az1983-395:62161] Signal: Aborted (6)
[fv-az1983-395:62161] Signal code:  (-6)
[fv-az1983-395:62161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac0b845330]
[fv-az1983-395:62161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac0b89eb2c]
[fv-az1983-395:62161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac0b84527e]
[fv-az1983-395:62161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac0b8288ff]
[fv-az1983-395:62161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac0bca5ff5]
[fv-az1983-395:62161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac0bcbb0da]
[fv-az1983-395:62161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac0bca5a55]
[fv-az1983-395:62161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac0bca5a6f]
[fv-az1983-395:62161] [ 8] plumed(+0x146dd)[0x5648ce03f6dd]
[fv-az1983-395:62161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac0b82a1ca]
[fv-az1983-395:62161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac0b82a28b]
[fv-az1983-395:62161] [11] plumed(+0x15365)[0x5648ce040365]
[fv-az1983-395:62161] *** End of error message ***
</pre>
{% endraw %}

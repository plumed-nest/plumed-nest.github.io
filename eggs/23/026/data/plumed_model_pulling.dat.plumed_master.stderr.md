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
[fv-az1983-395:62177] *** Process received signal ***
[fv-az1983-395:62177] Signal: Aborted (6)
[fv-az1983-395:62177] Signal code:  (-6)
[fv-az1983-395:62177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed76045330]
[fv-az1983-395:62177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed7609eb2c]
[fv-az1983-395:62177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed7604527e]
[fv-az1983-395:62177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed760288ff]
[fv-az1983-395:62177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed764a5ff5]
[fv-az1983-395:62177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed764bb0da]
[fv-az1983-395:62177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed764a5a55]
[fv-az1983-395:62177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed764a5a6f]
[fv-az1983-395:62177] [ 8] plumed_master(+0x146dd)[0x55fc51cff6dd]
[fv-az1983-395:62177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed7602a1ca]
[fv-az1983-395:62177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed7602a28b]
[fv-az1983-395:62177] [11] plumed_master(+0x15365)[0x55fc51d00365]
[fv-az1983-395:62177] *** End of error message ***
</pre>
{% endraw %}

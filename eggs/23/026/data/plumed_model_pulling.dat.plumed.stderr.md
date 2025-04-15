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
[fv-az1277-646:62662] *** Process received signal ***
[fv-az1277-646:62662] Signal: Aborted (6)
[fv-az1277-646:62662] Signal code:  (-6)
[fv-az1277-646:62662] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe55b045330]
[fv-az1277-646:62662] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe55b09eb2c]
[fv-az1277-646:62662] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe55b04527e]
[fv-az1277-646:62662] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe55b0288ff]
[fv-az1277-646:62662] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe55b4a5ff5]
[fv-az1277-646:62662] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe55b4bb0da]
[fv-az1277-646:62662] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe55b4a5a55]
[fv-az1277-646:62662] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe55b4a5a6f]
[fv-az1277-646:62662] [ 8] plumed(+0x146dd)[0x56551c3c66dd]
[fv-az1277-646:62662] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe55b02a1ca]
[fv-az1277-646:62662] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe55b02a28b]
[fv-az1277-646:62662] [11] plumed(+0x15365)[0x56551c3c7365]
[fv-az1277-646:62662] *** End of error message ***
</pre>
{% endraw %}

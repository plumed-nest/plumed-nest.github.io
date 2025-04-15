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
[fv-az1277-646:62678] *** Process received signal ***
[fv-az1277-646:62678] Signal: Aborted (6)
[fv-az1277-646:62678] Signal code:  (-6)
[fv-az1277-646:62678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc108a45330]
[fv-az1277-646:62678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc108a9eb2c]
[fv-az1277-646:62678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc108a4527e]
[fv-az1277-646:62678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc108a288ff]
[fv-az1277-646:62678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc108ea5ff5]
[fv-az1277-646:62678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc108ebb0da]
[fv-az1277-646:62678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc108ea5a55]
[fv-az1277-646:62678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc108ea5a6f]
[fv-az1277-646:62678] [ 8] plumed_master(+0x146dd)[0x55a6b2c366dd]
[fv-az1277-646:62678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc108a2a1ca]
[fv-az1277-646:62678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc108a2a28b]
[fv-az1277-646:62678] [11] plumed_master(+0x15365)[0x55a6b2c37365]
[fv-az1277-646:62678] *** End of error message ***
</pre>
{% endraw %}

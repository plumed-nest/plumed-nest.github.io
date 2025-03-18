**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:63914] *** Process received signal ***
[fv-az1377-740:63914] Signal: Aborted (6)
[fv-az1377-740:63914] Signal code:  (-6)
[fv-az1377-740:63914] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff465e45330]
[fv-az1377-740:63914] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff465e9eb2c]
[fv-az1377-740:63914] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff465e4527e]
[fv-az1377-740:63914] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff465e288ff]
[fv-az1377-740:63914] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4662a5ff5]
[fv-az1377-740:63914] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4662bb0da]
[fv-az1377-740:63914] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4662a5a55]
[fv-az1377-740:63914] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4662a5a6f]
[fv-az1377-740:63914] [ 8] plumed(+0x146dd)[0x55d726fd96dd]
[fv-az1377-740:63914] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff465e2a1ca]
[fv-az1377-740:63914] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff465e2a28b]
[fv-az1377-740:63914] [11] plumed(+0x15365)[0x55d726fda365]
[fv-az1377-740:63914] *** End of error message ***
</pre>
{% endraw %}

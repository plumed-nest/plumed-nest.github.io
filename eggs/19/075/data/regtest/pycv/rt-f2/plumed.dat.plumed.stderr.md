**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1947-163:67796] *** Process received signal ***
[fv-az1947-163:67796] Signal: Aborted (6)
[fv-az1947-163:67796] Signal code:  (-6)
[fv-az1947-163:67796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99eea45330]
[fv-az1947-163:67796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99eea9eb2c]
[fv-az1947-163:67796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99eea4527e]
[fv-az1947-163:67796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99eea288ff]
[fv-az1947-163:67796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99eeea5ff5]
[fv-az1947-163:67796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99eeebb0da]
[fv-az1947-163:67796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99eeea5a55]
[fv-az1947-163:67796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99eeea5a6f]
[fv-az1947-163:67796] [ 8] plumed(+0x146dd)[0x5638e71f86dd]
[fv-az1947-163:67796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99eea2a1ca]
[fv-az1947-163:67796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99eea2a28b]
[fv-az1947-163:67796] [11] plumed(+0x15365)[0x5638e71f9365]
[fv-az1947-163:67796] *** End of error message ***
</pre>
{% endraw %}

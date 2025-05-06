**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az1333-314:67298] *** Process received signal ***
[fv-az1333-314:67298] Signal: Aborted (6)
[fv-az1333-314:67298] Signal code:  (-6)
[fv-az1333-314:67298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1ebc45330]
[fv-az1333-314:67298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1ebc9eb2c]
[fv-az1333-314:67298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1ebc4527e]
[fv-az1333-314:67298] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1ebc288ff]
[fv-az1333-314:67298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1ec0a5ff5]
[fv-az1333-314:67298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1ec0bb0da]
[fv-az1333-314:67298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1ec0a5a55]
[fv-az1333-314:67298] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1ec0a5a6f]
[fv-az1333-314:67298] [ 8] plumed_master(+0x146dd)[0x55f8aedb86dd]
[fv-az1333-314:67298] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1ebc2a1ca]
[fv-az1333-314:67298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1ebc2a28b]
[fv-az1333-314:67298] [11] plumed_master(+0x15365)[0x55f8aedb9365]
[fv-az1333-314:67298] *** End of error message ***
</pre>
{% endraw %}

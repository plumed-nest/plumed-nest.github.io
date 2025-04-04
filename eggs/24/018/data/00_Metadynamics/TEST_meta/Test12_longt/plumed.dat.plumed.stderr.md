**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:06605] *** Process received signal ***
[fv-az1360-658:06605] Signal: Aborted (6)
[fv-az1360-658:06605] Signal code:  (-6)
[fv-az1360-658:06605] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2bfa245330]
[fv-az1360-658:06605] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2bfa29eb2c]
[fv-az1360-658:06605] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2bfa24527e]
[fv-az1360-658:06605] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2bfa2288ff]
[fv-az1360-658:06605] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2bfa6a5ff5]
[fv-az1360-658:06605] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2bfa6bb0da]
[fv-az1360-658:06605] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2bfa6a5a55]
[fv-az1360-658:06605] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2bfa6a5a6f]
[fv-az1360-658:06605] [ 8] plumed(+0x146dd)[0x564a900486dd]
[fv-az1360-658:06605] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2bfa22a1ca]
[fv-az1360-658:06605] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2bfa22a28b]
[fv-az1360-658:06605] [11] plumed(+0x15365)[0x564a90049365]
[fv-az1360-658:06605] *** End of error message ***
</pre>
{% endraw %}

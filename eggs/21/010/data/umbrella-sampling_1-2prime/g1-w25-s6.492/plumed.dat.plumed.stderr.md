**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:11293] *** Process received signal ***
[fv-az1719-476:11293] Signal: Aborted (6)
[fv-az1719-476:11293] Signal code:  (-6)
[fv-az1719-476:11293] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f854ca45330]
[fv-az1719-476:11293] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f854ca9eb2c]
[fv-az1719-476:11293] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f854ca4527e]
[fv-az1719-476:11293] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f854ca288ff]
[fv-az1719-476:11293] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f854cea5ff5]
[fv-az1719-476:11293] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f854cebb0da]
[fv-az1719-476:11293] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f854cea5a55]
[fv-az1719-476:11293] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f854cea5a6f]
[fv-az1719-476:11293] [ 8] plumed(+0x146dd)[0x5627370e36dd]
[fv-az1719-476:11293] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f854ca2a1ca]
[fv-az1719-476:11293] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f854ca2a28b]
[fv-az1719-476:11293] [11] plumed(+0x15365)[0x5627370e4365]
[fv-az1719-476:11293] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:10933] *** Process received signal ***
[fv-az1719-476:10933] Signal: Aborted (6)
[fv-az1719-476:10933] Signal code:  (-6)
[fv-az1719-476:10933] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efda3245330]
[fv-az1719-476:10933] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efda329eb2c]
[fv-az1719-476:10933] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efda324527e]
[fv-az1719-476:10933] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efda32288ff]
[fv-az1719-476:10933] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efda36a5ff5]
[fv-az1719-476:10933] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efda36bb0da]
[fv-az1719-476:10933] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efda36a5a55]
[fv-az1719-476:10933] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efda36a5a6f]
[fv-az1719-476:10933] [ 8] plumed(+0x146dd)[0x56385ca926dd]
[fv-az1719-476:10933] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efda322a1ca]
[fv-az1719-476:10933] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efda322a28b]
[fv-az1719-476:10933] [11] plumed(+0x15365)[0x56385ca93365]
[fv-az1719-476:10933] *** End of error message ***
</pre>
{% endraw %}

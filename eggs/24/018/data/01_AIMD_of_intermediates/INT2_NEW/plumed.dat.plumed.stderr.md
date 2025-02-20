**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:06408] *** Process received signal ***
[fv-az1444-322:06408] Signal: Aborted (6)
[fv-az1444-322:06408] Signal code:  (-6)
[fv-az1444-322:06408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff63a645330]
[fv-az1444-322:06408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff63a69eb2c]
[fv-az1444-322:06408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff63a64527e]
[fv-az1444-322:06408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff63a6288ff]
[fv-az1444-322:06408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff63aaa5ff5]
[fv-az1444-322:06408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff63aabb0da]
[fv-az1444-322:06408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff63aaa5a55]
[fv-az1444-322:06408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff63aaa5a6f]
[fv-az1444-322:06408] [ 8] plumed(+0x146dd)[0x55f33aa916dd]
[fv-az1444-322:06408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff63a62a1ca]
[fv-az1444-322:06408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff63a62a28b]
[fv-az1444-322:06408] [11] plumed(+0x15365)[0x55f33aa92365]
[fv-az1444-322:06408] *** End of error message ***
</pre>
{% endraw %}

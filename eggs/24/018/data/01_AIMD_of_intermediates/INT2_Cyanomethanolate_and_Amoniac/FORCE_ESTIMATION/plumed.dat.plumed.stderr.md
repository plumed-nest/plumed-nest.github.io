**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:06303] *** Process received signal ***
[fv-az1444-322:06303] Signal: Aborted (6)
[fv-az1444-322:06303] Signal code:  (-6)
[fv-az1444-322:06303] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f932ba45330]
[fv-az1444-322:06303] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f932ba9eb2c]
[fv-az1444-322:06303] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f932ba4527e]
[fv-az1444-322:06303] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f932ba288ff]
[fv-az1444-322:06303] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f932bea5ff5]
[fv-az1444-322:06303] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f932bebb0da]
[fv-az1444-322:06303] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f932bea5a55]
[fv-az1444-322:06303] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f932bea5a6f]
[fv-az1444-322:06303] [ 8] plumed(+0x146dd)[0x564ac89346dd]
[fv-az1444-322:06303] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f932ba2a1ca]
[fv-az1444-322:06303] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f932ba2a28b]
[fv-az1444-322:06303] [11] plumed(+0x15365)[0x564ac8935365]
[fv-az1444-322:06303] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:06146] *** Process received signal ***
[fv-az1444-322:06146] Signal: Aborted (6)
[fv-az1444-322:06146] Signal code:  (-6)
[fv-az1444-322:06146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe7cba45330]
[fv-az1444-322:06146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe7cba9eb2c]
[fv-az1444-322:06146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe7cba4527e]
[fv-az1444-322:06146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe7cba288ff]
[fv-az1444-322:06146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe7cbea5ff5]
[fv-az1444-322:06146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe7cbebb0da]
[fv-az1444-322:06146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe7cbea5a55]
[fv-az1444-322:06146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe7cbea5a6f]
[fv-az1444-322:06146] [ 8] plumed(+0x146dd)[0x55f6ea69c6dd]
[fv-az1444-322:06146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe7cba2a1ca]
[fv-az1444-322:06146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe7cba2a28b]
[fv-az1444-322:06146] [11] plumed(+0x15365)[0x55f6ea69d365]
[fv-az1444-322:06146] *** End of error message ***
</pre>
{% endraw %}

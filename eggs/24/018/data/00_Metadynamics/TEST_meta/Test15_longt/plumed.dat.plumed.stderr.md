**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:61044] *** Process received signal ***
[fv-az787-589:61044] Signal: Aborted (6)
[fv-az787-589:61044] Signal code:  (-6)
[fv-az787-589:61044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9470645330]
[fv-az787-589:61044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f947069eb2c]
[fv-az787-589:61044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f947064527e]
[fv-az787-589:61044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94706288ff]
[fv-az787-589:61044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9470aa5ff5]
[fv-az787-589:61044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9470abb0da]
[fv-az787-589:61044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9470aa5a55]
[fv-az787-589:61044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9470aa5a6f]
[fv-az787-589:61044] [ 8] plumed(+0x146dd)[0x55c7b92426dd]
[fv-az787-589:61044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f947062a1ca]
[fv-az787-589:61044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f947062a28b]
[fv-az787-589:61044] [11] plumed(+0x15365)[0x55c7b9243365]
[fv-az787-589:61044] *** End of error message ***
</pre>
{% endraw %}

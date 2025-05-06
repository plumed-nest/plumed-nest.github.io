**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1696-883:67457] *** Process received signal ***
[fv-az1696-883:67457] Signal: Aborted (6)
[fv-az1696-883:67457] Signal code:  (-6)
[fv-az1696-883:67457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc21645330]
[fv-az1696-883:67457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc2169eb2c]
[fv-az1696-883:67457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc2164527e]
[fv-az1696-883:67457] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc216288ff]
[fv-az1696-883:67457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc21aa5ff5]
[fv-az1696-883:67457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc21abb0da]
[fv-az1696-883:67457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc21aa5a55]
[fv-az1696-883:67457] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc21aa5a6f]
[fv-az1696-883:67457] [ 8] plumed_master(+0x146dd)[0x558d40ffd6dd]
[fv-az1696-883:67457] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc2162a1ca]
[fv-az1696-883:67457] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc2162a28b]
[fv-az1696-883:67457] [11] plumed_master(+0x15365)[0x558d40ffe365]
[fv-az1696-883:67457] *** End of error message ***
</pre>
{% endraw %}

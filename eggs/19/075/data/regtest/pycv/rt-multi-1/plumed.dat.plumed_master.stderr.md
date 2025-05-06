**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1696-883:67818] *** Process received signal ***
[fv-az1696-883:67818] Signal: Aborted (6)
[fv-az1696-883:67818] Signal code:  (-6)
[fv-az1696-883:67818] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f28c8845330]
[fv-az1696-883:67818] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f28c889eb2c]
[fv-az1696-883:67818] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f28c884527e]
[fv-az1696-883:67818] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28c88288ff]
[fv-az1696-883:67818] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28c8ca5ff5]
[fv-az1696-883:67818] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28c8cbb0da]
[fv-az1696-883:67818] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28c8ca5a55]
[fv-az1696-883:67818] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28c8ca5a6f]
[fv-az1696-883:67818] [ 8] plumed_master(+0x146dd)[0x55840a1676dd]
[fv-az1696-883:67818] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f28c882a1ca]
[fv-az1696-883:67818] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f28c882a28b]
[fv-az1696-883:67818] [11] plumed_master(+0x15365)[0x55840a168365]
[fv-az1696-883:67818] *** End of error message ***
</pre>
{% endraw %}

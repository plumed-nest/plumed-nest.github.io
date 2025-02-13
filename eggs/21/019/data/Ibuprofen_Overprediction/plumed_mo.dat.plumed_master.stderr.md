**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az1390-170:07386] *** Process received signal ***
[fv-az1390-170:07386] Signal: Aborted (6)
[fv-az1390-170:07386] Signal code:  (-6)
[fv-az1390-170:07386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb2ba45330]
[fv-az1390-170:07386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb2ba9eb2c]
[fv-az1390-170:07386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb2ba4527e]
[fv-az1390-170:07386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb2ba288ff]
[fv-az1390-170:07386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb2bea5ff5]
[fv-az1390-170:07386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb2bebb0da]
[fv-az1390-170:07386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb2bea5a55]
[fv-az1390-170:07386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb2bea5a6f]
[fv-az1390-170:07386] [ 8] plumed_master(+0x146dd)[0x558a07c156dd]
[fv-az1390-170:07386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb2ba2a1ca]
[fv-az1390-170:07386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb2ba2a28b]
[fv-az1390-170:07386] [11] plumed_master(+0x15365)[0x558a07c16365]
[fv-az1390-170:07386] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmmklqx:10283] *** Process received signal ***
[runnervmmklqx:10283] Signal: Aborted (6)
[runnervmmklqx:10283] Signal code:  (-6)
[runnervmmklqx:10283] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa3e7645330]
[runnervmmklqx:10283] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa3e769eb2c]
[runnervmmklqx:10283] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa3e764527e]
[runnervmmklqx:10283] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3e76288ff]
[runnervmmklqx:10283] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3e7aa5ff5]
[runnervmmklqx:10283] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3e7abb0da]
[runnervmmklqx:10283] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3e7aa5a55]
[runnervmmklqx:10283] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3e7aa5a6f]
[runnervmmklqx:10283] [ 8] plumed(+0x146dd)[0x5637bc1656dd]
[runnervmmklqx:10283] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa3e762a1ca]
[runnervmmklqx:10283] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa3e762a28b]
[runnervmmklqx:10283] [11] plumed(+0x15365)[0x5637bc166365]
[runnervmmklqx:10283] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06503] *** Process received signal ***
[runnervmmklqx:06503] Signal: Aborted (6)
[runnervmmklqx:06503] Signal code:  (-6)
[runnervmmklqx:06503] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa08ba45330]
[runnervmmklqx:06503] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa08ba9eb2c]
[runnervmmklqx:06503] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa08ba4527e]
[runnervmmklqx:06503] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa08ba288ff]
[runnervmmklqx:06503] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa08bea5ff5]
[runnervmmklqx:06503] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa08bebb0da]
[runnervmmklqx:06503] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa08bea5a55]
[runnervmmklqx:06503] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa08bea5a6f]
[runnervmmklqx:06503] [ 8] plumed(+0x146dd)[0x55d52175f6dd]
[runnervmmklqx:06503] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa08ba2a1ca]
[runnervmmklqx:06503] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa08ba2a28b]
[runnervmmklqx:06503] [11] plumed(+0x15365)[0x55d521760365]
[runnervmmklqx:06503] *** End of error message ***
</pre>
{% endraw %}

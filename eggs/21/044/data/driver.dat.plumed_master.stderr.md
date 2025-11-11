**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmw9dnm:10299] *** Process received signal ***
[runnervmw9dnm:10299] Signal: Aborted (6)
[runnervmw9dnm:10299] Signal code:  (-6)
[runnervmw9dnm:10299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd2a845330]
[runnervmw9dnm:10299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd2a89eb2c]
[runnervmw9dnm:10299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd2a84527e]
[runnervmw9dnm:10299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd2a8288ff]
[runnervmw9dnm:10299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd2aca5ff5]
[runnervmw9dnm:10299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd2acbb0da]
[runnervmw9dnm:10299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd2aca5a55]
[runnervmw9dnm:10299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd2aca5a6f]
[runnervmw9dnm:10299] [ 8] plumed_master(+0x146dd)[0x563ac961a6dd]
[runnervmw9dnm:10299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd2a82a1ca]
[runnervmw9dnm:10299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd2a82a28b]
[runnervmw9dnm:10299] [11] plumed_master(+0x15365)[0x563ac961b365]
[runnervmw9dnm:10299] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:07518] *** Process received signal ***
[runnervmw9dnm:07518] Signal: Aborted (6)
[runnervmw9dnm:07518] Signal code:  (-6)
[runnervmw9dnm:07518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a4a645330]
[runnervmw9dnm:07518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a4a69eb2c]
[runnervmw9dnm:07518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a4a64527e]
[runnervmw9dnm:07518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a4a6288ff]
[runnervmw9dnm:07518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a4aaa5ff5]
[runnervmw9dnm:07518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a4aabb0da]
[runnervmw9dnm:07518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a4aaa5a55]
[runnervmw9dnm:07518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a4aaa5a6f]
[runnervmw9dnm:07518] [ 8] plumed_master(+0x146dd)[0x55802241f6dd]
[runnervmw9dnm:07518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a4a62a1ca]
[runnervmw9dnm:07518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a4a62a28b]
[runnervmw9dnm:07518] [11] plumed_master(+0x15365)[0x558022420365]
[runnervmw9dnm:07518] *** End of error message ***
</pre>
{% endraw %}

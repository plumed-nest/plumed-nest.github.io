**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmw9dnm:10640] *** Process received signal ***
[runnervmw9dnm:10640] Signal: Aborted (6)
[runnervmw9dnm:10640] Signal code:  (-6)
[runnervmw9dnm:10640] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe5c045330]
[runnervmw9dnm:10640] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe5c09eb2c]
[runnervmw9dnm:10640] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe5c04527e]
[runnervmw9dnm:10640] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe5c0288ff]
[runnervmw9dnm:10640] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe5c4a5ff5]
[runnervmw9dnm:10640] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe5c4bb0da]
[runnervmw9dnm:10640] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe5c4a5a55]
[runnervmw9dnm:10640] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe5c4a5a6f]
[runnervmw9dnm:10640] [ 8] plumed_master(+0x146dd)[0x55a46c88d6dd]
[runnervmw9dnm:10640] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe5c02a1ca]
[runnervmw9dnm:10640] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe5c02a28b]
[runnervmw9dnm:10640] [11] plumed_master(+0x15365)[0x55a46c88e365]
[runnervmw9dnm:10640] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmw9dnm:13086] *** Process received signal ***
[runnervmw9dnm:13086] Signal: Aborted (6)
[runnervmw9dnm:13086] Signal code:  (-6)
[runnervmw9dnm:13086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe56045330]
[runnervmw9dnm:13086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe5609eb2c]
[runnervmw9dnm:13086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe5604527e]
[runnervmw9dnm:13086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe560288ff]
[runnervmw9dnm:13086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe564a5ff5]
[runnervmw9dnm:13086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe564bb0da]
[runnervmw9dnm:13086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe564a5a55]
[runnervmw9dnm:13086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe564a5a6f]
[runnervmw9dnm:13086] [ 8] plumed_master(+0x146dd)[0x55a62fc816dd]
[runnervmw9dnm:13086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe5602a1ca]
[runnervmw9dnm:13086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe5602a28b]
[runnervmw9dnm:13086] [11] plumed_master(+0x15365)[0x55a62fc82365]
[runnervmw9dnm:13086] *** End of error message ***
</pre>
{% endraw %}

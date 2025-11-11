**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:11693] *** Process received signal ***
[runnervmw9dnm:11693] Signal: Aborted (6)
[runnervmw9dnm:11693] Signal code:  (-6)
[runnervmw9dnm:11693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcdba45330]
[runnervmw9dnm:11693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcdba9eb2c]
[runnervmw9dnm:11693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcdba4527e]
[runnervmw9dnm:11693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcdba288ff]
[runnervmw9dnm:11693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcdbea5ff5]
[runnervmw9dnm:11693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcdbebb0da]
[runnervmw9dnm:11693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcdbea5a55]
[runnervmw9dnm:11693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcdbea5a6f]
[runnervmw9dnm:11693] [ 8] plumed_master(+0x146dd)[0x556f8f37d6dd]
[runnervmw9dnm:11693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcdba2a1ca]
[runnervmw9dnm:11693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcdba2a28b]
[runnervmw9dnm:11693] [11] plumed_master(+0x15365)[0x556f8f37e365]
[runnervmw9dnm:11693] *** End of error message ***
</pre>
{% endraw %}

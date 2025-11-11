**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:11161] *** Process received signal ***
[runnervmw9dnm:11161] Signal: Aborted (6)
[runnervmw9dnm:11161] Signal code:  (-6)
[runnervmw9dnm:11161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f191c645330]
[runnervmw9dnm:11161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f191c69eb2c]
[runnervmw9dnm:11161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f191c64527e]
[runnervmw9dnm:11161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f191c6288ff]
[runnervmw9dnm:11161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f191caa5ff5]
[runnervmw9dnm:11161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f191cabb0da]
[runnervmw9dnm:11161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f191caa5a55]
[runnervmw9dnm:11161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f191caa5a6f]
[runnervmw9dnm:11161] [ 8] plumed(+0x146dd)[0x55ba5a9906dd]
[runnervmw9dnm:11161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f191c62a1ca]
[runnervmw9dnm:11161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f191c62a28b]
[runnervmw9dnm:11161] [11] plumed(+0x15365)[0x55ba5a991365]
[runnervmw9dnm:11161] *** End of error message ***
</pre>
{% endraw %}

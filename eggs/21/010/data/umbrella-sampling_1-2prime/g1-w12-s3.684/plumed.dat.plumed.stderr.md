**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w12-s3.684/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:10956] *** Process received signal ***
[runnervmw9dnm:10956] Signal: Aborted (6)
[runnervmw9dnm:10956] Signal code:  (-6)
[runnervmw9dnm:10956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7962445330]
[runnervmw9dnm:10956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f796249eb2c]
[runnervmw9dnm:10956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f796244527e]
[runnervmw9dnm:10956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79624288ff]
[runnervmw9dnm:10956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79628a5ff5]
[runnervmw9dnm:10956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79628bb0da]
[runnervmw9dnm:10956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79628a5a55]
[runnervmw9dnm:10956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79628a5a6f]
[runnervmw9dnm:10956] [ 8] plumed(+0x146dd)[0x55acd9f966dd]
[runnervmw9dnm:10956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f796242a1ca]
[runnervmw9dnm:10956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f796242a28b]
[runnervmw9dnm:10956] [11] plumed(+0x15365)[0x55acd9f97365]
[runnervmw9dnm:10956] *** End of error message ***
</pre>
{% endraw %}

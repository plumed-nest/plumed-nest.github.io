**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06880] *** Process received signal ***
[runnervmw9dnm:06880] Signal: Aborted (6)
[runnervmw9dnm:06880] Signal code:  (-6)
[runnervmw9dnm:06880] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f909d845330]
[runnervmw9dnm:06880] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f909d89eb2c]
[runnervmw9dnm:06880] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f909d84527e]
[runnervmw9dnm:06880] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f909d8288ff]
[runnervmw9dnm:06880] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f909dca5ff5]
[runnervmw9dnm:06880] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f909dcbb0da]
[runnervmw9dnm:06880] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f909dca5a55]
[runnervmw9dnm:06880] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f909dca5a6f]
[runnervmw9dnm:06880] [ 8] plumed(+0x146dd)[0x5595c034d6dd]
[runnervmw9dnm:06880] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f909d82a1ca]
[runnervmw9dnm:06880] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f909d82a28b]
[runnervmw9dnm:06880] [11] plumed(+0x15365)[0x5595c034e365]
[runnervmw9dnm:06880] *** End of error message ***
</pre>
{% endraw %}

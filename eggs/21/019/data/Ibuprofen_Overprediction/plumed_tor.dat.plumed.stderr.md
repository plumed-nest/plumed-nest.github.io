**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmw9dnm:13070] *** Process received signal ***
[runnervmw9dnm:13070] Signal: Aborted (6)
[runnervmw9dnm:13070] Signal code:  (-6)
[runnervmw9dnm:13070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f964ba45330]
[runnervmw9dnm:13070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f964ba9eb2c]
[runnervmw9dnm:13070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f964ba4527e]
[runnervmw9dnm:13070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f964ba288ff]
[runnervmw9dnm:13070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f964bea5ff5]
[runnervmw9dnm:13070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f964bebb0da]
[runnervmw9dnm:13070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f964bea5a55]
[runnervmw9dnm:13070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f964bea5a6f]
[runnervmw9dnm:13070] [ 8] plumed(+0x146dd)[0x5573c7c396dd]
[runnervmw9dnm:13070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f964ba2a1ca]
[runnervmw9dnm:13070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f964ba2a28b]
[runnervmw9dnm:13070] [11] plumed(+0x15365)[0x5573c7c3a365]
[runnervmw9dnm:13070] *** End of error message ***
</pre>
{% endraw %}

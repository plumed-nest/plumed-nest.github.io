**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmw9dnm:06323] *** Process received signal ***
[runnervmw9dnm:06323] Signal: Aborted (6)
[runnervmw9dnm:06323] Signal code:  (-6)
[runnervmw9dnm:06323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4590a45330]
[runnervmw9dnm:06323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4590a9eb2c]
[runnervmw9dnm:06323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4590a4527e]
[runnervmw9dnm:06323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4590a288ff]
[runnervmw9dnm:06323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4590ea5ff5]
[runnervmw9dnm:06323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4590ebb0da]
[runnervmw9dnm:06323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4590ea5a55]
[runnervmw9dnm:06323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4590ea5a6f]
[runnervmw9dnm:06323] [ 8] plumed(+0x146dd)[0x55a5aad3d6dd]
[runnervmw9dnm:06323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4590a2a1ca]
[runnervmw9dnm:06323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4590a2a28b]
[runnervmw9dnm:06323] [11] plumed(+0x15365)[0x55a5aad3e365]
[runnervmw9dnm:06323] *** End of error message ***
</pre>
{% endraw %}

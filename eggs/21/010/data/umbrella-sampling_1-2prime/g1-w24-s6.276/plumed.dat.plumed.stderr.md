**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:07184] *** Process received signal ***
[runnervmvrwv9:07184] Signal: Aborted (6)
[runnervmvrwv9:07184] Signal code:  (-6)
[runnervmvrwv9:07184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16f8045330]
[runnervmvrwv9:07184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16f809eb2c]
[runnervmvrwv9:07184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16f804527e]
[runnervmvrwv9:07184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16f80288ff]
[runnervmvrwv9:07184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16f84a5ff5]
[runnervmvrwv9:07184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16f84bb0da]
[runnervmvrwv9:07184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16f84a5a55]
[runnervmvrwv9:07184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16f84a5a6f]
[runnervmvrwv9:07184] [ 8] plumed(+0x146dd)[0x5582fe03d6dd]
[runnervmvrwv9:07184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16f802a1ca]
[runnervmvrwv9:07184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16f802a28b]
[runnervmvrwv9:07184] [11] plumed(+0x15365)[0x5582fe03e365]
[runnervmvrwv9:07184] *** End of error message ***
</pre>
{% endraw %}

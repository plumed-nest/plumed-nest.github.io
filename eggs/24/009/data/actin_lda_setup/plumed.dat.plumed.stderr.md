**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmvrwv9:06967] *** Process received signal ***
[runnervmvrwv9:06967] Signal: Aborted (6)
[runnervmvrwv9:06967] Signal code:  (-6)
[runnervmvrwv9:06967] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f13a2a45330]
[runnervmvrwv9:06967] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f13a2a9eb2c]
[runnervmvrwv9:06967] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f13a2a4527e]
[runnervmvrwv9:06967] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13a2a288ff]
[runnervmvrwv9:06967] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13a2ea5ff5]
[runnervmvrwv9:06967] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13a2ebb0da]
[runnervmvrwv9:06967] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13a2ea5a55]
[runnervmvrwv9:06967] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13a2ea5a6f]
[runnervmvrwv9:06967] [ 8] plumed(+0x146dd)[0x5626c0b946dd]
[runnervmvrwv9:06967] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f13a2a2a1ca]
[runnervmvrwv9:06967] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f13a2a2a28b]
[runnervmvrwv9:06967] [11] plumed(+0x15365)[0x5626c0b95365]
[runnervmvrwv9:06967] *** End of error message ***
</pre>
{% endraw %}

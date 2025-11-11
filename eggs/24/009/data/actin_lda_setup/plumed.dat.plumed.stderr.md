**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmw9dnm:07462] *** Process received signal ***
[runnervmw9dnm:07462] Signal: Aborted (6)
[runnervmw9dnm:07462] Signal code:  (-6)
[runnervmw9dnm:07462] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5abfc45330]
[runnervmw9dnm:07462] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5abfc9eb2c]
[runnervmw9dnm:07462] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5abfc4527e]
[runnervmw9dnm:07462] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5abfc288ff]
[runnervmw9dnm:07462] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ac00a5ff5]
[runnervmw9dnm:07462] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ac00bb0da]
[runnervmw9dnm:07462] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ac00a5a55]
[runnervmw9dnm:07462] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ac00a5a6f]
[runnervmw9dnm:07462] [ 8] plumed(+0x146dd)[0x55718044d6dd]
[runnervmw9dnm:07462] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5abfc2a1ca]
[runnervmw9dnm:07462] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5abfc2a28b]
[runnervmw9dnm:07462] [11] plumed(+0x15365)[0x55718044e365]
[runnervmw9dnm:07462] *** End of error message ***
</pre>
{% endraw %}

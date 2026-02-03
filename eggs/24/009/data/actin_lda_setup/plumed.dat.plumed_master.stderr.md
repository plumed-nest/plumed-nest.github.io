**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmkj6or:05433] *** Process received signal ***
[runnervmkj6or:05433] Signal: Aborted (6)
[runnervmkj6or:05433] Signal code:  (-6)
[runnervmkj6or:05433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf4ec45330]
[runnervmkj6or:05433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf4ec9eb2c]
[runnervmkj6or:05433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf4ec4527e]
[runnervmkj6or:05433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf4ec288ff]
[runnervmkj6or:05433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf4f0a5ff5]
[runnervmkj6or:05433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf4f0bb0da]
[runnervmkj6or:05433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf4f0a5a55]
[runnervmkj6or:05433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf4f0a5a6f]
[runnervmkj6or:05433] [ 8] plumed_master(+0x146dd)[0x55df37ef26dd]
[runnervmkj6or:05433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf4ec2a1ca]
[runnervmkj6or:05433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf4ec2a28b]
[runnervmkj6or:05433] [11] plumed_master(+0x15365)[0x55df37ef3365]
[runnervmkj6or:05433] *** End of error message ***
</pre>
{% endraw %}

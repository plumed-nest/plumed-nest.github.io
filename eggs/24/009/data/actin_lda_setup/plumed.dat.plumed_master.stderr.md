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
[pkrvmq0rgcvqdmg:07097] *** Process received signal ***
[pkrvmq0rgcvqdmg:07097] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07097] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbaf3845330]
[pkrvmq0rgcvqdmg:07097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbaf389eb2c]
[pkrvmq0rgcvqdmg:07097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbaf384527e]
[pkrvmq0rgcvqdmg:07097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbaf38288ff]
[pkrvmq0rgcvqdmg:07097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbaf3ca5ff5]
[pkrvmq0rgcvqdmg:07097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbaf3cbb0da]
[pkrvmq0rgcvqdmg:07097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbaf3ca5a55]
[pkrvmq0rgcvqdmg:07097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbaf3ca5a6f]
[pkrvmq0rgcvqdmg:07097] [ 8] plumed_master(+0x146dd)[0x565519cb46dd]
[pkrvmq0rgcvqdmg:07097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbaf382a1ca]
[pkrvmq0rgcvqdmg:07097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbaf382a28b]
[pkrvmq0rgcvqdmg:07097] [11] plumed_master(+0x15365)[0x565519cb5365]
[pkrvmq0rgcvqdmg:07097] *** End of error message ***
</pre>
{% endraw %}

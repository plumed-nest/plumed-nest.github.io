**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmmklqx:04821] *** Process received signal ***
[runnervmmklqx:04821] Signal: Aborted (6)
[runnervmmklqx:04821] Signal code:  (-6)
[runnervmmklqx:04821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b93845330]
[runnervmmklqx:04821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b9389eb2c]
[runnervmmklqx:04821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b9384527e]
[runnervmmklqx:04821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b938288ff]
[runnervmmklqx:04821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b93ca5ff5]
[runnervmmklqx:04821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b93cbb0da]
[runnervmmklqx:04821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b93ca5a55]
[runnervmmklqx:04821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b93ca5a6f]
[runnervmmklqx:04821] [ 8] plumed(+0x146dd)[0x55953b0646dd]
[runnervmmklqx:04821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b9382a1ca]
[runnervmmklqx:04821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b9382a28b]
[runnervmmklqx:04821] [11] plumed(+0x15365)[0x55953b065365]
[runnervmmklqx:04821] *** End of error message ***
</pre>
{% endraw %}

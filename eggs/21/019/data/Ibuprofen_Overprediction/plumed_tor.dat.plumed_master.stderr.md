**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmgx7h7:09184] *** Process received signal ***
[runnervmgx7h7:09184] Signal: Aborted (6)
[runnervmgx7h7:09184] Signal code:  (-6)
[runnervmgx7h7:09184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff03845330]
[runnervmgx7h7:09184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff0389ec0c]
[runnervmgx7h7:09184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff0384527e]
[runnervmgx7h7:09184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff038288ff]
[runnervmgx7h7:09184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff03ca5ff5]
[runnervmgx7h7:09184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff03cbb0da]
[runnervmgx7h7:09184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff03ca5a55]
[runnervmgx7h7:09184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff03ca5a6f]
[runnervmgx7h7:09184] [ 8] plumed_master(+0x146dd)[0x561db9cc66dd]
[runnervmgx7h7:09184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff0382a1ca]
[runnervmgx7h7:09184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff0382a28b]
[runnervmgx7h7:09184] [11] plumed_master(+0x15365)[0x561db9cc7365]
[runnervmgx7h7:09184] *** End of error message ***
</pre>
{% endraw %}

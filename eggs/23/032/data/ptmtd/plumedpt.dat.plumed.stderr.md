**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmgx7h7:06468] *** Process received signal ***
[runnervmgx7h7:06468] Signal: Aborted (6)
[runnervmgx7h7:06468] Signal code:  (-6)
[runnervmgx7h7:06468] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd806245330]
[runnervmgx7h7:06468] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd80629ec0c]
[runnervmgx7h7:06468] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd80624527e]
[runnervmgx7h7:06468] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8062288ff]
[runnervmgx7h7:06468] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8066a5ff5]
[runnervmgx7h7:06468] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8066bb0da]
[runnervmgx7h7:06468] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8066a5a55]
[runnervmgx7h7:06468] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8066a5a6f]
[runnervmgx7h7:06468] [ 8] plumed(+0x146dd)[0x558f172216dd]
[runnervmgx7h7:06468] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd80622a1ca]
[runnervmgx7h7:06468] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd80622a28b]
[runnervmgx7h7:06468] [11] plumed(+0x15365)[0x558f17222365]
[runnervmgx7h7:06468] *** End of error message ***
</pre>
{% endraw %}

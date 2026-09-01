**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmgx7h7:06413] *** Process received signal ***
[runnervmgx7h7:06413] Signal: Aborted (6)
[runnervmgx7h7:06413] Signal code:  (-6)
[runnervmgx7h7:06413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbaea845330]
[runnervmgx7h7:06413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbaea89ec0c]
[runnervmgx7h7:06413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbaea84527e]
[runnervmgx7h7:06413] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbaea8288ff]
[runnervmgx7h7:06413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbaeaca5ff5]
[runnervmgx7h7:06413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbaeacbb0da]
[runnervmgx7h7:06413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbaeaca5a55]
[runnervmgx7h7:06413] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbaeaca5a6f]
[runnervmgx7h7:06413] [ 8] plumed(+0x146dd)[0x5619cc15d6dd]
[runnervmgx7h7:06413] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbaea82a1ca]
[runnervmgx7h7:06413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbaea82a28b]
[runnervmgx7h7:06413] [11] plumed(+0x15365)[0x5619cc15e365]
[runnervmgx7h7:06413] *** End of error message ***
</pre>
{% endraw %}

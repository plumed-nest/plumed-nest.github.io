**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[runnervmgx7h7:09527] *** Process received signal ***
[runnervmgx7h7:09527] Signal: Aborted (6)
[runnervmgx7h7:09527] Signal code:  (-6)
[runnervmgx7h7:09527] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ab8845330]
[runnervmgx7h7:09527] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ab889ec0c]
[runnervmgx7h7:09527] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ab884527e]
[runnervmgx7h7:09527] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ab88288ff]
[runnervmgx7h7:09527] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ab8ca5ff5]
[runnervmgx7h7:09527] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ab8cbb0da]
[runnervmgx7h7:09527] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ab8ca5a55]
[runnervmgx7h7:09527] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ab8ca5a6f]
[runnervmgx7h7:09527] [ 8] plumed(+0x146dd)[0x5609bdd2d6dd]
[runnervmgx7h7:09527] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ab882a1ca]
[runnervmgx7h7:09527] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ab882a28b]
[runnervmgx7h7:09527] [11] plumed(+0x15365)[0x5609bdd2e365]
[runnervmgx7h7:09527] *** End of error message ***
</pre>
{% endraw %}

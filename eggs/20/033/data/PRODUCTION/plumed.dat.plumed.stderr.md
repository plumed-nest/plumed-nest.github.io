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
[runnervm76f27:09082] *** Process received signal ***
[runnervm76f27:09082] Signal: Aborted (6)
[runnervm76f27:09082] Signal code:  (-6)
[runnervm76f27:09082] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa9b845330]
[runnervm76f27:09082] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa9b89ec0c]
[runnervm76f27:09082] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa9b84527e]
[runnervm76f27:09082] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa9b8288ff]
[runnervm76f27:09082] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa9bca5ff5]
[runnervm76f27:09082] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa9bcbb0da]
[runnervm76f27:09082] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa9bca5a55]
[runnervm76f27:09082] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa9bca5a6f]
[runnervm76f27:09082] [ 8] plumed(+0x146dd)[0x557a100af6dd]
[runnervm76f27:09082] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa9b82a1ca]
[runnervm76f27:09082] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa9b82a28b]
[runnervm76f27:09082] [11] plumed(+0x15365)[0x557a100b0365]
[runnervm76f27:09082] *** End of error message ***
</pre>
{% endraw %}

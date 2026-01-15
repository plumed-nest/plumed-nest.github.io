**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33592] *** Process received signal ***
[runnervmmtnos:33592] Signal: Aborted (6)
[runnervmmtnos:33592] Signal code:  (-6)
[runnervmmtnos:33592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe649e45330]
[runnervmmtnos:33592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe649e9eb2c]
[runnervmmtnos:33592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe649e4527e]
[runnervmmtnos:33592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe649e288ff]
[runnervmmtnos:33592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe64a2a5ff5]
[runnervmmtnos:33592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe64a2bb0da]
[runnervmmtnos:33592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe64a2a5a55]
[runnervmmtnos:33592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe64a2a5a6f]
[runnervmmtnos:33592] [ 8] plumed(+0x146dd)[0x560b6469d6dd]
[runnervmmtnos:33592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe649e2a1ca]
[runnervmmtnos:33592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe649e2a28b]
[runnervmmtnos:33592] [11] plumed(+0x15365)[0x560b6469e365]
[runnervmmtnos:33592] *** End of error message ***
</pre>
{% endraw %}

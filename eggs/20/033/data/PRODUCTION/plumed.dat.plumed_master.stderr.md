**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervmkj6or:09667] *** Process received signal ***
[runnervmkj6or:09667] Signal: Aborted (6)
[runnervmkj6or:09667] Signal code:  (-6)
[runnervmkj6or:09667] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4ac645330]
[runnervmkj6or:09667] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4ac69eb2c]
[runnervmkj6or:09667] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4ac64527e]
[runnervmkj6or:09667] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4ac6288ff]
[runnervmkj6or:09667] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4acaa5ff5]
[runnervmkj6or:09667] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4acabb0da]
[runnervmkj6or:09667] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4acaa5a55]
[runnervmkj6or:09667] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4acaa5a6f]
[runnervmkj6or:09667] [ 8] plumed_master(+0x146dd)[0x5555b8f006dd]
[runnervmkj6or:09667] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4ac62a1ca]
[runnervmkj6or:09667] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4ac62a28b]
[runnervmkj6or:09667] [11] plumed_master(+0x15365)[0x5555b8f01365]
[runnervmkj6or:09667] *** End of error message ***
</pre>
{% endraw %}

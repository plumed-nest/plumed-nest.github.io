**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[pkrvmf6wy0o8zjz:68482] *** Process received signal ***
[pkrvmf6wy0o8zjz:68482] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68482] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c66645330]
[pkrvmf6wy0o8zjz:68482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c6669eb2c]
[pkrvmf6wy0o8zjz:68482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c6664527e]
[pkrvmf6wy0o8zjz:68482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c666288ff]
[pkrvmf6wy0o8zjz:68482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c66aa5ff5]
[pkrvmf6wy0o8zjz:68482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c66abb0da]
[pkrvmf6wy0o8zjz:68482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c66aa5a55]
[pkrvmf6wy0o8zjz:68482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c66aa5a6f]
[pkrvmf6wy0o8zjz:68482] [ 8] plumed(+0x146dd)[0x55c19d2396dd]
[pkrvmf6wy0o8zjz:68482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c6662a1ca]
[pkrvmf6wy0o8zjz:68482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c6662a28b]
[pkrvmf6wy0o8zjz:68482] [11] plumed(+0x15365)[0x55c19d23a365]
[pkrvmf6wy0o8zjz:68482] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[runnervm0kj6c:10299] *** Process received signal ***
[runnervm0kj6c:10299] Signal: Aborted (6)
[runnervm0kj6c:10299] Signal code:  (-6)
[runnervm0kj6c:10299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff075e45330]
[runnervm0kj6c:10299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff075e9eb2c]
[runnervm0kj6c:10299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff075e4527e]
[runnervm0kj6c:10299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff075e288ff]
[runnervm0kj6c:10299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0762a5ff5]
[runnervm0kj6c:10299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0762bb0da]
[runnervm0kj6c:10299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0762a5a55]
[runnervm0kj6c:10299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0762a5a6f]
[runnervm0kj6c:10299] [ 8] plumed(+0x146dd)[0x55936a7406dd]
[runnervm0kj6c:10299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff075e2a1ca]
[runnervm0kj6c:10299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff075e2a28b]
[runnervm0kj6c:10299] [11] plumed(+0x15365)[0x55936a741365]
[runnervm0kj6c:10299] *** End of error message ***
</pre>
{% endraw %}

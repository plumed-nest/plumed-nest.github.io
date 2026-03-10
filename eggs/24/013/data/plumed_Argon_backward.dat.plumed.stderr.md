**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervm0kj6c:04624] *** Process received signal ***
[runnervm0kj6c:04624] Signal: Aborted (6)
[runnervm0kj6c:04624] Signal code:  (-6)
[runnervm0kj6c:04624] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7b1845330]
[runnervm0kj6c:04624] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7b189eb2c]
[runnervm0kj6c:04624] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7b184527e]
[runnervm0kj6c:04624] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7b18288ff]
[runnervm0kj6c:04624] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7b1ca5ff5]
[runnervm0kj6c:04624] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7b1cbb0da]
[runnervm0kj6c:04624] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7b1ca5a55]
[runnervm0kj6c:04624] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7b1ca5a6f]
[runnervm0kj6c:04624] [ 8] plumed(+0x146dd)[0x563c64b496dd]
[runnervm0kj6c:04624] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7b182a1ca]
[runnervm0kj6c:04624] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7b182a28b]
[runnervm0kj6c:04624] [11] plumed(+0x15365)[0x563c64b4a365]
[runnervm0kj6c:04624] *** End of error message ***
</pre>
{% endraw %}

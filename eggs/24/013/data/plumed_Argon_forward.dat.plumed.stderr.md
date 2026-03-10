**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervm0kj6c:04675] *** Process received signal ***
[runnervm0kj6c:04675] Signal: Aborted (6)
[runnervm0kj6c:04675] Signal code:  (-6)
[runnervm0kj6c:04675] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf0de45330]
[runnervm0kj6c:04675] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf0de9eb2c]
[runnervm0kj6c:04675] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf0de4527e]
[runnervm0kj6c:04675] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf0de288ff]
[runnervm0kj6c:04675] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf0e2a5ff5]
[runnervm0kj6c:04675] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf0e2bb0da]
[runnervm0kj6c:04675] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf0e2a5a55]
[runnervm0kj6c:04675] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf0e2a5a6f]
[runnervm0kj6c:04675] [ 8] plumed(+0x146dd)[0x5603a79cb6dd]
[runnervm0kj6c:04675] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf0de2a1ca]
[runnervm0kj6c:04675] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf0de2a28b]
[runnervm0kj6c:04675] [11] plumed(+0x15365)[0x5603a79cc365]
[runnervm0kj6c:04675] *** End of error message ***
</pre>
{% endraw %}

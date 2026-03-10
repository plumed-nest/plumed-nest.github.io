**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervm0kj6c:07381] *** Process received signal ***
[runnervm0kj6c:07381] Signal: Aborted (6)
[runnervm0kj6c:07381] Signal code:  (-6)
[runnervm0kj6c:07381] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f33cf645330]
[runnervm0kj6c:07381] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f33cf69eb2c]
[runnervm0kj6c:07381] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f33cf64527e]
[runnervm0kj6c:07381] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33cf6288ff]
[runnervm0kj6c:07381] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33cfaa5ff5]
[runnervm0kj6c:07381] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33cfabb0da]
[runnervm0kj6c:07381] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33cfaa5a55]
[runnervm0kj6c:07381] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33cfaa5a6f]
[runnervm0kj6c:07381] [ 8] plumed(+0x146dd)[0x559530f606dd]
[runnervm0kj6c:07381] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f33cf62a1ca]
[runnervm0kj6c:07381] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f33cf62a28b]
[runnervm0kj6c:07381] [11] plumed(+0x15365)[0x559530f61365]
[runnervm0kj6c:07381] *** End of error message ***
</pre>
{% endraw %}

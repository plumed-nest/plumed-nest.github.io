**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervm0kj6c:10208] *** Process received signal ***
[runnervm0kj6c:10208] Signal: Aborted (6)
[runnervm0kj6c:10208] Signal code:  (-6)
[runnervm0kj6c:10208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd931845330]
[runnervm0kj6c:10208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd93189eb2c]
[runnervm0kj6c:10208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd93184527e]
[runnervm0kj6c:10208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9318288ff]
[runnervm0kj6c:10208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd931ca5ff5]
[runnervm0kj6c:10208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd931cbb0da]
[runnervm0kj6c:10208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd931ca5a55]
[runnervm0kj6c:10208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd931ca5a6f]
[runnervm0kj6c:10208] [ 8] plumed(+0x146dd)[0x56342d01e6dd]
[runnervm0kj6c:10208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd93182a1ca]
[runnervm0kj6c:10208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd93182a28b]
[runnervm0kj6c:10208] [11] plumed(+0x15365)[0x56342d01f365]
[runnervm0kj6c:10208] *** End of error message ***
</pre>
{% endraw %}

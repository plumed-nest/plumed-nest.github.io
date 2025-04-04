**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[fv-az805-507:12617] *** Process received signal ***
[fv-az805-507:12617] Signal: Aborted (6)
[fv-az805-507:12617] Signal code:  (-6)
[fv-az805-507:12617] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2e1645330]
[fv-az805-507:12617] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2e169eb2c]
[fv-az805-507:12617] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2e164527e]
[fv-az805-507:12617] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2e16288ff]
[fv-az805-507:12617] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2e1aa5ff5]
[fv-az805-507:12617] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2e1abb0da]
[fv-az805-507:12617] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2e1aa5a55]
[fv-az805-507:12617] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2e1aa5a6f]
[fv-az805-507:12617] [ 8] plumed_master(+0x146dd)[0x55fdf6aa46dd]
[fv-az805-507:12617] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2e162a1ca]
[fv-az805-507:12617] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2e162a28b]
[fv-az805-507:12617] [11] plumed_master(+0x15365)[0x55fdf6aa5365]
[fv-az805-507:12617] *** End of error message ***
</pre>
{% endraw %}

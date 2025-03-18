**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az1950-95:65339] *** Process received signal ***
[fv-az1950-95:65339] Signal: Aborted (6)
[fv-az1950-95:65339] Signal code:  (-6)
[fv-az1950-95:65339] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11eb845330]
[fv-az1950-95:65339] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11eb89eb2c]
[fv-az1950-95:65339] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11eb84527e]
[fv-az1950-95:65339] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11eb8288ff]
[fv-az1950-95:65339] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11ebca5ff5]
[fv-az1950-95:65339] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11ebcbb0da]
[fv-az1950-95:65339] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11ebca5a55]
[fv-az1950-95:65339] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11ebca5a6f]
[fv-az1950-95:65339] [ 8] plumed_master(+0x146dd)[0x560b237cb6dd]
[fv-az1950-95:65339] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11eb82a1ca]
[fv-az1950-95:65339] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11eb82a28b]
[fv-az1950-95:65339] [11] plumed_master(+0x15365)[0x560b237cc365]
[fv-az1950-95:65339] *** End of error message ***
</pre>
{% endraw %}

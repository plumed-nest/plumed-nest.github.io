**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:12283] *** Process received signal ***
[pkrvmpptgkbjq6m:12283] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12283] Signal code:  (-6)
[pkrvmpptgkbjq6m:12283] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9982845330]
[pkrvmpptgkbjq6m:12283] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f998289eb2c]
[pkrvmpptgkbjq6m:12283] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f998284527e]
[pkrvmpptgkbjq6m:12283] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99828288ff]
[pkrvmpptgkbjq6m:12283] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9982ca5ff5]
[pkrvmpptgkbjq6m:12283] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9982cbb0da]
[pkrvmpptgkbjq6m:12283] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9982ca5a55]
[pkrvmpptgkbjq6m:12283] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9982ca5a6f]
[pkrvmpptgkbjq6m:12283] [ 8] plumed_master(+0x146dd)[0x55dc1b3ce6dd]
[pkrvmpptgkbjq6m:12283] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f998282a1ca]
[pkrvmpptgkbjq6m:12283] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f998282a28b]
[pkrvmpptgkbjq6m:12283] [11] plumed_master(+0x15365)[0x55dc1b3cf365]
[pkrvmpptgkbjq6m:12283] *** End of error message ***
</pre>
{% endraw %}

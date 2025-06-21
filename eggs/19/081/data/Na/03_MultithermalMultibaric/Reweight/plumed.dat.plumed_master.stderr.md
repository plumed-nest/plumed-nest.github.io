**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:14244] *** Process received signal ***
[pkrvmxyh4eaekms:14244] Signal: Aborted (6)
[pkrvmxyh4eaekms:14244] Signal code:  (-6)
[pkrvmxyh4eaekms:14244] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6426a45330]
[pkrvmxyh4eaekms:14244] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6426a9eb2c]
[pkrvmxyh4eaekms:14244] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6426a4527e]
[pkrvmxyh4eaekms:14244] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6426a288ff]
[pkrvmxyh4eaekms:14244] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6426ea5ff5]
[pkrvmxyh4eaekms:14244] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6426ebb0da]
[pkrvmxyh4eaekms:14244] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6426ea5a55]
[pkrvmxyh4eaekms:14244] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6426ea5a6f]
[pkrvmxyh4eaekms:14244] [ 8] plumed_master(+0x146dd)[0x563e2c6da6dd]
[pkrvmxyh4eaekms:14244] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6426a2a1ca]
[pkrvmxyh4eaekms:14244] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6426a2a28b]
[pkrvmxyh4eaekms:14244] [11] plumed_master(+0x15365)[0x563e2c6db365]
[pkrvmxyh4eaekms:14244] *** End of error message ***
</pre>
{% endraw %}

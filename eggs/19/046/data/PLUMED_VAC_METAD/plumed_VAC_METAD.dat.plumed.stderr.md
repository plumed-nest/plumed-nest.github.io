**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC_METAD/plumed_VAC_METAD.dat   
(download [zipped raw stdout](plumed_VAC_METAD.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: FPS LABEL=fps REFERENCE=Faidon_new_ref.pdb LIGAND=lig ANCHOR=2481 POINTS=-0.5910,0.3486,-1.6694,-0.6214,0.5475,-1.2516
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fc2f5cce4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fc2f5cce428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fc2f5cd002a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fc2f630884d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fc2f63066b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fc2f6306701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fc2f6306919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fc2f5cb9830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14160] *** End of error message ***
</pre>
{% endraw %}

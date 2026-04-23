# Headless-Cellprofiler
conda environment for running cellprofiler headlessly


This has been packaged with conda pack -n cellprofiler -o cellprofiler_env.tar.gz --ignore-missing-files

in your conda env folder (e.g. /opt/anaconda3/envs/)

create a directory cellprofiler
mkdir -p /opt/anaconda3/envs/cellprofiler

Then unpack the contents to the cellprofiler directory.
tar -xzf cellprofiler_env.tar.gz -C /opt/anaconda3/envs/cellprofiler
and then (confirm if conda-unpack exists)
/opt/anaconda3/envs/cellprofiler/bin/conda-unpack

(video attached) Then, from your base, try conda activate cellprofiler
Then, cppipe

# Headless CellProfiler

This package contains a pre-built conda environment for running CellProfiler headlessly using cppipe.

---

## 📦 Contents
- cellprofiler_env.tar.gz — packaged conda environment  
- (optional) pipeline files (.cppipe)  
- (optional) input data  

---

## ⚙️ Requirements
- macOS  
- Conda installed (Anaconda / Miniconda / Miniforge)  

---

## 🚀 Installation

### 1. Locate your conda environments directory

Run:

    conda info | grep "envs directories"

Example output:

    /opt/anaconda3/envs

---

### 2. Create the environment folder

    mkdir -p /opt/anaconda3/envs/cellprofiler

---

### 3. Unpack the environment

    tar -xzf cellprofiler_env.tar.gz -C /opt/anaconda3/envs/cellprofiler

---

### 4. Fix environment paths

    /opt/anaconda3/envs/cellprofiler/bin/conda-unpack

If conda-unpack is not found, skip this step.

---

## ▶️ Usage

Activate the environment:

    conda activate cellprofiler

Run CellProfiler:

    cppipe

---

## 📝 Notes
- The install path (/opt/anaconda3/envs/) may differ depending on your conda setup  
  (for example: ~/anaconda3/envs/ or ~/miniconda3/envs/)  
- This environment is built for macOS and may not work on other operating systems  
- If activation fails, try:

    conda activate /opt/anaconda3/envs/cellprofiler  

---

## ✅ Summary
1. Extract into your conda envs directory  
2. Run conda-unpack  
3. Activate with conda activate cellprofiler  
4. Run cppipe

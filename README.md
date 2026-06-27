# CI/CD Apache Spark

## Aktywacja środowiska

### Opcja 1: Conda (zalecana)

Przy pierwszym uruchomieniu zainicjuj conda dla swojego shella:

```bash
conda init zsh
```

Zamknij i otwórz terminal ponownie, a następnie aktywuj środowisko:

```bash
conda activate apache_spark
```

Jeśli środowisko nie istnieje, utwórz je z pliku `environment.yml`:

```bash
conda env create -f environment.yml
conda activate apache_spark
```

### Opcja 2: venv (Python 3.14)

```bash
source .venv/bin/activate
```

Aby wyjść ze środowiska:

```bash
conda deactivate   # dla conda
deactivate         # dla venv
```

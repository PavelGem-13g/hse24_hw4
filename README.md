# hse24_hw4

## Подготовил

Пашенцев Павел Владимирович

# Код

[Первая часть](/src/Pashentsev_4_Py_ipynb_.ipynb)
[Вторая часть](/src/Pashentsev_4_R_ipynb_.ipynb)


# Часть 1

[Ссылка на All.counts](/data/ALL.counts)

## MultiQC

General Statistics

![](/multiqc_plots/general_stats_table.png)

Sequence Counts

![](/multiqc_plots/fastqc_sequence_counts_plot.png)

Sequence Quality Histograms

![](/multiqc_plots/fastqc_per_base_sequence_quality_plot.png)

Per Sequence Quality Scores

![](/multiqc_plots/fastqc_per_sequence_quality_scores_plot.png)

Per Sequence GC Content

![](/multiqc_plots/fastqc_per_sequence_gc_content_plot.png)

Per Base N Content

![](/multiqc_plots/fastqc_per_base_n_content_plot.png)

Sequence Duplication Levels

![](/multiqc_plots/fastqc_sequence_duplication_levels_plot.png)

Status Checks

![](/multiqc_plots/fastqc-status-check-heatmap.png)

## Сводная таблица

| ID | Тип | Общее число исходных чтений | Число и процент успешно откартированных чтений (не уникальные) | Число и процент успешно откартированных чтений (уникальные) | Общее число чтений, попавших на гены |
|----------|:----------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414635** | контрольный | 20956475  | 20715476, 98.85% | 18637053, 87.1% | 16463013 |
| **SRR3414636** | контрольный | 20307147  | 20073615, 98.85% | 18032679, 86.5% | 15942667 |
| **SRR3414637** | контрольный | 20385570  | 20149097, 98.84% | 18043406, 86.3% | 15914380 |
| **SRR3414629** | перепрограммированный | 21106089  | 20863369, 98.86% | 18573565, 88.0% | 16224313 |
| **SRR3414630** | перепрограммированный | 15244711  | 15077019, 98.90% | 13320505, 87.8% | 11583775 |
| **SRR3414631** | перепрограммированный | 24244069  | 23965262, 98.85% | 21159606, 87.5% | 18613501 |

# Бонусная часть

[Ссылка на differentially_expressed_genes.txt](/data/differentially_expressed_genes.txt)

## DESeq2

![](/DESeq2/_1.png)

![](/DESeq2/_2.png)

![](/DESeq2/_3.png)

![](/DESeq2/_4.png)

![](/DESeq2/_5.png)

![](/DESeq2/_6.png)
FROM python:3.13.1-alpine

RUN apk add --no-cache bash

RUN pip install pandas numpy matplotlib seaborn plotly

COPY --from=scripts --chmod=777 methylation/plot_umap.py /scripts/methylation/plot_umap.py
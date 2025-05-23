***Dates LMTD MTD CM LM LLM***

```
with  my_yt as (select current_date+interval '-1' day yt )
      select date_trunc('month', yt +interval '-3' month) m_3_start,
            date_trunc('month', yt +interval '-2' month)+ interval'-1' day m_3_end,
            date_trunc('month', yt +interval '-2' month) m_2_start,
            date_trunc('month', yt +interval '-1' month)+ interval'-1' day m_2_end,
            date_trunc('month', yt +interval '-1' month) m_1_start,
            date_trunc('month', yt +interval '0' month)+ interval'-1' day m_1_end,
            date_trunc('month', yt) CM_start,
            yt,
            yt +interval '-1' month LMTD,
            yt +interval '-2' month LLMTD
      from my_yt
```

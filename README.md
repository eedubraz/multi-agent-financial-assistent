# Multi-Agent Financial Assistant 📊

A sophisticated financial analysis system powered by multiple AI agents to provide real-time market insights, stock analysis, and financial recommendations.

## 🎯 Project Overview

This project implements a multi-agent system that leverages artificial intelligence to analyze financial markets and provide comprehensive insights. The system includes specialized agents for:

- Financial analysis and stock recommendations
- Real-time market data processing
- News aggregation and sentiment analysis
- Investment strategy recommendations

## 🚀 Features

- Real-time stock price monitoring
- Analyst recommendations aggregation
- Latest financial news integration
- Custom financial reports generation

## 🛠️ Technologies Used

- Python
- Natural Language Processing (NLP)
- Multi-agent AI Architecture
- Financial APIs Integration

## 📊 Example Output

```
┏━ Message ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                                                                                                                         ┃
┃ Summarize analyst recommendation and share the latest news for NVDA                                                     ┃
┃                                                                                                                         ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
┏━ Response (12.0s) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                                                                                                                         ┃
┃ Running:                                                                                                                ┃
┃                                                                                                                         ┃
┃  • transfer_task_to_finance_ai_agent(task_description=Retrieve the latest analyst recommendation for the company with   ┃
┃    ticker symbol NVDA, expected_output=A summary of the latest analyst recommendation, additional_information=Please    ┃
┃    use the get_analyst_recommendations tool)                                                                            ┃
┃  • transfer_task_to_web_search_agent(task_description=Find the latest news for the company with ticker symbol NVDA,     ┃
┃    expected_output=A list of the latest news articles, additional_information=Please use the duckduckgo_news tool)      ┃
┃                                                                                                                         ┃
┃ Here is the latest information on the company with the ticker symbol NVDA:                                              ┃
┃                                                                                                                         ┃
┃ Analyst Recommendation:                                                                                                 ┃
┃                                                                                                                         ┃
┃  • Buy: 48                                                                                                              ┃
┃  • Hold: 4                                                                                                              ┃
┃  • Sell: 0                                                                                                              ┃
┃  • Strong Buy: 12                                                                                                       ┃
┃  • Strong Sell: 0                                                                                                       ┃
┃                                                                                                                         ┃
┃ The data is based on the most recent month.                                                                             ┃
┃                                                                                                                         ┃
┃ Latest News:                                                                                                            ┃
┃                                                                                                                         ┃
┃  1 Why Is Nvidia (NVDA) Stock Rocketing Higher Today - Shares of leading designer of graphics chips Nvidia              ┃
┃    (NASDAQ:NVDA) jumped 5.1% in the morning session after market sentiment improved ahead of CEO Jensen Huang's speech  ┃
┃    at CES (Consumer Electronic Show) 2025. Read more                                                                    ┃
┃                                                                                                                         ┃
┃ 🌆 Nvidia Stock Rocketing                                                                                               ┃
┃                                                                                                                         ┃
┃  2 Nvidia stock pops ahead of Jensen Huang's CES keynote. Here's what investors can expect to hear from the top chip    ┃
┃    exec, according to BofA. - "We still see CES as a positive catalyst, re-asserting NVDA's platform                    ┃
┃    dominance/opportunity in high-growth markets," Bank of America said. Read more                                       ┃
┃                                                                                                                         ┃
┃ 🌆 Nvidia Keynote                                                                                                       ┃
┃                                                                                                                         ┃
┃  3 Is NVIDIA Corp (NASDAQ:NVDA) Among Israel Englander's Top Stock Picks Heading Into 2025? - We recently compiled a    ┃
┃    list of the Billionaire Israel Englander's Top 10 Stock Picks Heading Into 2025. In this article, we are going to    ┃
┃    take a look at where NVIDIA Corp (NASDAQ:NVDA) stands against the other stock picks. Read more                       ┃
┃                                                                                                                         ┃
┃ 🌆 Israel Englander's Top Stock Picks                                                                                   ┃
┃                                                                                                                         ┃
┃  4 Nvidia: Expect Shares To Soar Higher On 2025's AI Spending Frenzy - Discover how Nvidia Corporation's revenue soared ┃
┃    in 2024, driven by hyperscaler investments in AI data centers, solidifying its dominance. Click for more on NVDA.    ┃
┃    Read more                                                                                                            ┃
┃                                                                                                                         ┃
┃ 🌆 Nvidia AI Spending                                                                                                   ┃
┃                                                                                                                         ┃
┃  5 Nvidia's stock heads for record close as AI chip trade reloads for fresh run higher - Foxconn earnings offer upbeat  ┃
┃    signs about the Blackwell ramp, and Nvidia CEO Jensen Huang's upcoming CEO keynote could further support the         ┃
┃    semiconductor sector. Read more                                                                                      ┃
┃                                                                                                                         ┃
┃ 🌆 Nvidia Record Close                                                                                                  ┃
┃                                                                                                                         ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
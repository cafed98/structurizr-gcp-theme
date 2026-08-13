# GCP Theme for Structurizr DSL
Google Cloud Platform theme for [Structurizr](https://structurizr.com/) with update icons, to create stunning [C4 Diagrams](https://c4model.com/). Original icons can be found [here](https://cloud.google.com/icons).
<br><br>
The theme follows the new guideline from Google and thus it includes two different icon categories:
- **Category Product Category**: The same category icon can be used for multiple products across Google Cloud offering. To know which product category a product belongs to, you can check the official [slides deck](https://services.google.com/fh/files/misc/google-cloud-product-icons.pdf).
- **Core Product Category**: core products carry their own unique icons, not a general product category icon. These are main services inside the GCP offering such as BigQuery, GKE ecc...

This theme has been created with `st` CLI. Available [here](https://github.com/FedericoCantarelli/st). Please note that `st` CLI is in a **very early stage** version. I mean, if I was in your shoes I definetely wouldn't use it, but we live in a free country, so feel free to give it a try.


## Usage
To use this theme, just add the following line to your view statement:
```dsl
views {
  ...
  themes https://raw.githubusercontent.com/cafed98/structurizr-gcp-theme/refs/heads/<version>/google-cloud-platform/theme.json
  }
```
You can replace `<your-version>` with the version you want to use. For example, if you want to use version 0, you can use `v0`. If you want to use the latest version, you can use `main`.

Then you can simply use the theme by assigning the TAG to your elements.

## Limitation
For the moment, Gemini Icon is not present since this repository has been created with `st` CLI and gemini icon wasn't included in Google icons pack.

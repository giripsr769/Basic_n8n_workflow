---

## 🚀 How to Import & Run in n8n

### Prerequisites
- An active **n8n** instance (Cloud or Self-Hosted Docker setup).
- OpenAI API credentials configured in n8n.

### Import Steps
1. Open your n8n dashboard.
2. Click **Workflows** > **Add Workflow**.
3. In the top-right menu (`...`), select **Import from File**.
4. Upload `First n8n Work Flow.json`.
5. Configure your **OpenAI Chat Model** credentials (`OpenAI account`).
6. Toggle the workflow to **Active**.
7. Open the Form Trigger URL to upload your raw CSV file and process your data!

---

## 📄 License
This project is open-source under the MIT License.
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(markdown_content)

print("README.md generated successfully.")

      - name: Push to hub
        env:
          HF_TOKEN: ${{ secrets.HF_TOKEN }}
        run: git push --force https://vasu1231:$HF_TOKEN@huggingface.co/spaces/vasu1231/chatbot-app main

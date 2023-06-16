

Using `conda`:
``` bash
cd search-sum
conda create -n ss-env python=3.10
conda activate ss-env
```

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory of the project. Inside the file, add your OpenAI API key:

```makefile
OPENAI_API_KEY=your_api_key_here
# M2 IREN (OASN2024) + M1 Droit

!!!!! In your programs, transitioning to the Python module 'openai' version >=1.0.0 (due to an update of openai in november 2023) involves modifying the following lines in the Python code:

import openai => becomes => from openai import OpenAI

openai.api_key = '****' => becomes => client = OpenAI(api_key='*****')

completion = openai.ChatCompletion.create() => becomes => completion = client.chat.completions.create()
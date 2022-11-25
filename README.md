# pythoncafe
import requests import re import argparse   parser = argparse.ArgumentParser(     description="Get list of links from a website" )   parser.add_argument("url", nargs="?", help="URL", default=None)   arguments = parser.parse_args()   use_arguments = True if arguments.url is not None else False

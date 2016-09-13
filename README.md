# server-end
this will interact with the server
from flask import Flask 
import sqlite3

app=main(Flask())

@app.run('/')

def index():
  return index.html
  
@app.route('/homel/')

def home():
  return hom,e.html
  
  
  
def write_db(data ,id , )

  try:
    con = lite.connect('test.db')
    
    cur = con.cursor()    
    cur.execute('SELECT SQLITE_VERSION()')
    
    data = cur.fetchone()
    
    print "SQLite version: %s" % data                
    
  except lite.Error, e:
     
    print "Error %s:" % e.args[0]
    sys.exit(1)
    

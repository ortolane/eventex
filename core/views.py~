# Create your views here.

#from django.http import HttpResponse
#from django.template import loader, Context

from django.shortcuts import render_to_response

def homepage(request):
    #t = loader.get_template('index.html')
    #c = Context()
    #content = t.render(c)
    #return HttpResponse(content)
    from django.conf import settings
    context = {'MEDIA_URL': settings.MEDIA_URL}
    return render_to_response('index.html', context)

